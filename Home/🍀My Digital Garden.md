---
Class: Default
Updated: 2023-12-10 11:07:45
Created: 2023-12-07 21:45:12
Links: "[[🏡My Home]]"
tags:
  - 🍀
---


The home of my Evergreen Notes

# Stones
Stones(![|20](https://worker.rahc.top/imgs/digital-garden/202311291126841.svg), dg-note-icon: 0) represents materials that may be generate creative ideas and thoughts.
```dataview
table Created
from #note 
where dg-note-icon = "0"
```

# Seedlings
Seedings(![|20](https://worker.rahc.top/imgs/digital-garden/202311291035533.svg), dg-note-icon: 1) represents the new ideas and thoughts, but not necessarily feasibility.
```dataview
table Created
from #note 
where dg-note-icon = "1"
```


## Saplings
Saplings(![|20](https://worker.rahc.top/imgs/digital-garden/202311291036902.svg), dg-note-icon: 2) represents an idea or perspective that has been formed through a certain period of observation and research, but still needs further development or maturation.
```dataview
table Created
from #note 
where dg-note-icon = "2"
```

## Flowers
Flowers (![|20](https://worker.rahc.top/imgs/digital-garden/202311291036541.svg), dg-note-icon: 3) represents an idea or perspective that can be output as a certain standard, such as outputting to a blog or academic paper.
```dataview
table Created
from #note 
where dg-note-icon = "3"
```

## Wilted
Wilted (![|20](https://worker.rahc.top/imgs/digital-garden/202311291037401.svg), dg-note-icon: 4) represents those outdated ideas or perspectives that have been preserved in the digital garden for historical reasons.
```dataview
table Created
from #note
where dg-note-icon = "4"
```
