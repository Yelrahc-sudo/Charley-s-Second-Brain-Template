---
Class: Note
Updated: 2023-12-10 11:19:25
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[🔁My Periodic Reviews]]"
tags:
  - note/yearly
priority: Medium
due: 
finished: 
started: 
project: 
resource: 
area: 
archived: 
last-review: 
status: Not Started
favorite: 
level: Raw Materials
para: Project
---


# <% tp.file.title %>


## Future Plan
### Action Items

- [ ] 
- [ ] 
- [ ] 

## Yearly Habits

## Projects
```dataview
table started, finished, due, area
from #project 
where !contains(file.name, "Template")
where date(today) - started <= dur(1 years)
```
### Reflection
#### Learning

## Recap

## Days
```dataview
LIST
FROM #note/monthly  
where date(today) - date(file.name) <= dur(1 years)
where !contains(file.name, "Template")
```
