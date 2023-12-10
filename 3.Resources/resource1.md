---
Class: Default
Updated: 2023-12-10 11:21:38
Created: 2023-12-10 17:27:12
Links: "[[🔭My Resources]]"
tags:
  - resource
---


# resource1
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
where resource = "resource1" and !contains(file.name, "Template")
```
### Inputs
```dataview
TABLE source
from #note/input
where resource = "resource1" and !contains(file.name, "Template")
```

### Thoughts
```dataview
list
from #note/thought
where resource = "resource1" and !contains(file.name, "Template")
```
