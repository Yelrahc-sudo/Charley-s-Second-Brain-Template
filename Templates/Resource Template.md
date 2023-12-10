---
Class: Default
Updated: 2023-12-10 11:21:38
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[🔭My Resources]]"
tags:
  - resource
---


# <% tp.file.title %>
## Notes

### Practices
- 
- 

### Tools

## Queries
### Notes
```dataview
list
from #note and !#note/input and !#note/thought
where resource = "<% tp.file.title %>" and !contains(file.name, "Template")
```
### Inputs
```dataview
TABLE source
from #note/input
where resource = "<% tp.file.title %>" and !contains(file.name, "Template")
```

### Thoughts
```dataview
list
from #note/thought
where resource = "<% tp.file.title %>" and !contains(file.name, "Template")
```
