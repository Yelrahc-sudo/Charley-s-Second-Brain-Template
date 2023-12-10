---
Class: Default
Updated: 2023-12-10 11:11:26
Created: 2023-12-07 17:05:27
Links: "[[🏡My Home]]"
tags:
  - 💭
---


# 💭My Thoughts
- Consider using thoughts as input that can create/add into already existing notes.
## Categories
- memories
	- anecodotes and experiences

- reflections
	- personal thoughts and lessons

- musings
	- random shower ideas
## Memories
```dataview
table Created
From #note/thought
where categories = "memories" and !contains(file.name, "Template")
SORT started desc
```
## Reflections
```dataview
table Created
From #note/thought
where categories = "reflections" and !contains(file.name, "Template")
SORT started desc
```

## Musings
```dataview
table Created
From #note/thought
where categories = "musings" and !contains(file.name, "Template")
SORT started desc
```

## All Unsorted
- 
- 
