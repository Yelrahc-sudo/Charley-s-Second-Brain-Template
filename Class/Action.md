---
limit: 100
mapWithTag: false
icon: activity
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: Default
savedViews: []
favoriteView: 
version: "2.16"
fields:
  - name: status
    type: Select
    options:
      valuesList:
        "1": Not Started
        "2": Doing
        "3": Paused
        "4": Done
        "5": Canceled
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: CRH1IO
  - name: started
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: EJYBd8
  - name: finished
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: GMa6rR
  - name: due
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: y7ZdC6
  - name: priority
    type: Select
    options:
      valuesList:
        "1": Low
        "2": Medium
        "3": High
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: DvKV0W
---
