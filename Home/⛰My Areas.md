---
Class: Default
Updated: 2023-12-08 17:37:13
Created: 2023-12-07 16:21:14
Links: "[[🏡My Home]]"
tags:
  - ⛰
---


# ⛰ My Areas

> [!Info]
> PARA Method in Obsidian MD > Areas and Resources

```button
name Create New Area
type command
action QuickAdd: Area
color purple
```
^button-m9bl

## Notes
```dataview
TABLE rows.file.link as File
FROM #note
WHERE area != ""
WHERE !contains(file.name, "Template")
flatten tags
group by tags
```
## All

```dataview
list
from #area
where !contains(file.name, "Template")
```
***
