---
Class: Default
Updated: 2023-12-08 17:36:45
Created: 2023-12-07 18:39:06
Links: "[[🏡My Home]]"
tags:
  - 🗃
---


# My Archives

Archiving is a bit complicated with links, so at the moment it's only set to notes that are in the actual folder.

## Query
```dataview
table Created, tags
from #project or #note 
where !contains(file.name, "Template")
where archived = True
```


References: