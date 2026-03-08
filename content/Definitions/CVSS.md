the system which determines the level of severity of a vulnerability

the two main sub-scores are:
- [[exploitability score]]
- [[impact score]]

Categorizing the score
0 None
0.1-3.9 Low
4.0-6.9 Medium
7.0-8.9 High
9.0-10.0 Critical

These steps determine the CVSS score
1. If impact == 0, return 0
2. if scope == unchanged, return (impact_score + exploitability_score)
3. if scope metric == changed, return ((impact_score + exploitability_score) * 1.08)
4. if result > 10, return 10
