---
Class: Project
Updated: 2023-12-09 17:45:19
Created: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
Links: "[[⚒My Projects]]"
tags:
  - project
due: 
finished: 
started: 
area: 
priority: 🟨
archived: 
status: ⚪
---

# <% tp.file.title %>

## Kanbans
```button
name Create New Kanban
type command
action QuickAdd: Kanban
```
^button-nw8f
%%Link the related kanban here%%

## Resources
### Notes
%%Add any non-connected notes or specific contexts here%%

#### Query
```dataview
list
from #note 
where project = "<% tp.file.title %>"
```

### External Links

## Planning
### Objective:
- 

### Key Results:
- 

### Obstacles and Their Solutions:
- 

### Timeframe:
%% Include links to related weeks or days %%
```dataview
LIST
FROM #note/daily or #note/weekly 
where project = "<% tp.file.title %>"
```

## Reflection
### Satisfied?
- 

### Improvements and Solutions Learned for the Future:
- 
