---
Class: Default
Updated: 2023-12-08 17:36:42
Created: 2023-12-07 21:35:56
Links: "[[🏡My Home]]"
tags:
  - 🧠
---

# 🧠My Second Brain

## Queries
### Projects
```dataview
table due
from #project
where !contains(file.name, "Template")
```
### Inputs
```dataview
table Status, Author
from #note/input
where !contains(file.name, "Template")
```

### Notes
```dataview
table Created
from #note 
where !contains(file.name, "Template")
```

