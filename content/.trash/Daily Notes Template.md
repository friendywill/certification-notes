---
created:
  "{{date}}" 
tags:
  - daily-notes
---

---
### 📅 Daily Questions
##### 🌜 Last night I...
- 

##### 🙌 One thing I'm excited about right now is...
- 

##### 🚀 One+ thing I plan to accomplish today is...
- [ ] 

##### 👎 One thing I'm struggling with today is...
- 

---
# 📝 Notes

---
### Notes created today
```dataview
List FROM "" WHERE file.cday = date({{date}}) SORT file.ctime asc
```

### Notes last touched today
```dataview
List FROM "" WHERE file.mday = date({{date}}) AND file.cday != date({{date}}) SORT file.mtime asc
```