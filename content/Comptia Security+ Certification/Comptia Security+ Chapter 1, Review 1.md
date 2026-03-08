---
tags:
  - review
  - chapters
  - practice
created: 03/02/2025
aliases:
---

How does Comptia define [[cybersecurity]]?
The practice of protecting technological information assets.

How does Comptia define [[cybersecurity professionals]]?
a person who is given responsibility for protection technological assets.

How has today's cybersecurity professional evolved?
Cyber security professionals now have many different specialisations and fields they can choose from, they are a much more integral part of any organisation, they have a lot more complexity to deal with, and they have to keep more up-to-date with the latest threats.

What are the different [[cybersecurity objectives]] and how do fulfil the mission of security?
The cybersecurity objectives are overarching goals to protect an organisation's technological information assets.
They aim to fulfil the mission of security by providing a benchmark that an organisation must meet which is designed to secure it's information assets.

How could organisations meet these [[cybersecurity objectives]]?
By performing a risk analysis, then a gap analysis to determine the risks that require the most attention, then allocating time and resources to implement security controls with the goal of closing the gap to that objective.

What are [[data breach risks]]? 
Potential ways of defining something that could happen that would compromise the CIA of data.

Who are the people causing fear of [[data breach risks]]?
Cyber criminals, terrorists, organised crime syndicates, government funded groups, organised hacktivist groups, insiders threats, even unsuspecting employees.

How are [[data breach risks]] caused?
Through some gap that hasn't been closed.

What is the [[DAD triad]]? How does it fulfil the goal it sets to achieve? 
The DAD triad stands for Denial, Alteration and Disclosure, they are the antithesis of the CIA triad.
The goal of the DAD triad is to show what you are mitigating when implementing the CIA triad, so for availability, you protect against denial, for integrity, you protect against alteration, and for confidentiality, you protect against disclosure.

What are the different  [[cybersecurity risk types]] and their respective [[cybersecurity risk type impacts]]?
The different data breach risks include:
- Financial data breach risk
  Where a company suffers monetary loss due to some cyber security incident, and example would be an attack impersonating a fake bank website, that an unsuspecting employee enters in the company's credit card details.
- Reputational damage
  Where some stakeholders lose some or all trust in the company due to some cyber security incident. An example would be if a company had customer details stored and leaked, customers would think twice before purchasing from that company again.
- Strategic risk
	Where the ability to execute a business plan as expected could be affected if some cybersecurity incident were to happen.
- Operational
	Where the day to day tasks are under risk of being less efficient, or stopped.
	This is similar to the strategic risk, where if an operational risk came to fruition and affected the operations for a significant enough amount of time, it would then affect the strategic plan of the company. If the affect is minimal on operations, it may not affect the business strategical plans. It is possible for a strategic risk to happen, and it would not immediately or ever affect the company's operations.
- Compliance
	This risk is more concerned about what could happen if an incident where to occur, and it exposed the company to which it was not following its legal obligations.

What are all of the different [[security control categories]]? Describe how a control would fall under that category.
- Technical
	Where the control is implemented at the cyber level and is automated, EG ACLs or firewall rules.
- Managerial
	The actual process of undertaking security risk management.
- Operational
	The security processes implemented in day to day tasks, to ensure those activities do not compromise CIA.
- Physical
	Where there is some form of tangible protection, EG biometric lock too a door or computer.
What are all of the different [[security control types]]? Describe how a control falls under a certain type.
- Preventative
	Where the control stops some potential attack from succeeding through some measure.
- Deterrent
	Where the control is intended to provide the adversary some reason or reasons not to partake in some attack. 
- Compensating
	When some risk cannot be solved through eliminating the underlying risk vector, so instead a compensating control is implemented. This control provides an alternative way to control a risk that may not be ideal, but does not have the same barrier that the ideal has. An example is legacy software on a legacy OS, it would be ideal to upgrade the OS, but not worth the time, or potentially may just be impossible, therefore you would compensate by isolating the environment on an air-gapped VM.
- Detective
	When some potential attack is logged where somebody is alerted within the organisation.
- Corrective
	When some potential attack has occurred, and this control will recover from the attack.
- Directive
	Procedures in place to get people to take some action after a potential security event has happened.

How would a [[gap analysis]] be done?
- To conduct a gap analysis, you must determine what the ideal security status could be, then figure out the current security posture. The different between the current and ideal security postures is the gap (what could be done).
What concepts exist for [[data protection]]? How do these protection mechanisms fulfil their role?
- Data encryption, which prevent disclosure and keeps confidentiality. The data is protected by making it unreadable, and can only be deciphered with the a secure key (symmetric or asymmetric).
- Data Loss Prevention, data is protected by detecting some sensitive data at some point, then deleting or encrypting that data to ensure confidentiality. There are agent-based DLP systems, where some endpoint process monitors the entire system for any potential sensitive data. There are also network-based DLP systems, which monitor network traffic.
- Data minimization
	Reducing the amount of sensitive data on a dataset, ideally by deleting it. But if the data cannot be deleted, data minimization can still be achieved whether through tokenization (essentially giving the sensitive data cell an ID, replacing the cell with the ID and placing the data somewhere secure alonside the ID), hashing (not recommended for columns with duplicate information), or making partial redactions (replacing a credit card number with X's then keeping the last 4 digits).
What is [[data exfiltration]]?
- Where data is lost to some adversary.
What are [[security controls]]? How is it related to a [[gap analysis]]?
- Security controls are measures put in place to mitigate risks from occurring, where they close the gap on the gap analysis.
What are the two different ways [[data loss prevention]] works?
- Agent-based and network based as explained above.
What are the mechanisms of action for [[data loss prevention]]?
- Data encryption
- Data deletion
What is [[digital rights management (DRM)]]?
What is [[data minimisation]]?
What are the different methods for [[data minimisation]] and how do they work?
What are the two types of [[access restrictions]]?
What is the different between [[segmentation]] and [[isolation]]?