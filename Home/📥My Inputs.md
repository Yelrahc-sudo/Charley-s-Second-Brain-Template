---
Class: Default
Updated: 2023-12-08 17:36:51
Created: 2023-12-07 17:49:04
Links: "[[🏡My Home]]"
tags:
  - 📥
---


# 📥My Inputs

```button
name Add Input
type command
action QuickAdd: Input
color blue
```
^button-poce


## Inputs Sorted
### Not Started 
```dataview
table started, finished, rating
From #note/input 
where status = "Not Started" and !contains(file.name, "Template")
SORT started desc
```
### Consuming Media 
```dataview
table started, finished, rating
From #note/input 
where status = "Consuming" and !contains(file.name, "Template")
SORT started desc
```
### Implementation 
```dataview
table started, finished, rating
From #note/input 
where status = "Implementation" and !contains(file.name, "Template")
SORT started desc
```

### Finished 
```dataview
table started, finished, rating
From #note/input 
where status = "Finished" and !contains(file.name, "Template")
SORT started desc
```

### Incomplete 
```dataview
table started, finished, rating
From #note/input 
where status = "Incomplete" and !contains(file.name, "Template")
SORT started desc
```
