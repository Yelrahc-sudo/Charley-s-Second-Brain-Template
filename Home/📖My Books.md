---
Class: Default
Updated: 2023-12-10 11:11:39
Created: 2023-12-07 17:02:43
Links: "[[🏡My Home]]"
tags:
  - 📖
---


## Kanban

### Not Started
```dataview
table started, finished, rating
from #note/book 
where status = "Not Started"
where !contains(file.name, "Template")
```

### Consuming Media
```dataview
table started, finished, rating
from #note/book 
where status = "Consuming" and !contains(file.name, "Template")
```

### Implementation
```dataview
table started, finished, rating
from #note/book 
where status = "Implementation" and !contains(file.name, "Template")
```
