---
limit: 100
mapWithTag: true
icon: clipboard-list
tagNames:
  - note
filesPaths: 
bookmarksGroups: 
excludes: 
extends: Action
savedViews: 
favoriteView: 
version: "2.52"
fields:
  - name: para
    type: Select
    options:
      valuesList:
        "1": Project
        "2": Area
        "3": Resource
        "4": Archive
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: 04z0ws
  - name: level
    type: Select
    options:
      valuesList:
        "1": Raw Materials
        "2": Distilled Notes
        "3": Outtakes
        "4": Work-in-process
        "5": Final Deliverable
        "6": Documents Created by Others
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: FMVbep
  - name: favorite
    type: Boolean
    options: {}
    path: ""
    id: 6WBCNh
  - name: status
    type: Select
    options:
      valuesList:
        "1": Not Started
        "2": To Be Daily Reviewed
        "3": To Be Weekly Reviewed
        "4": To Be Monthly Reviewed
        "5": Reviewing
        "6": Writing
        "8": Finished
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: q7NseT
  - name: last-review
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: H2PvC7
  - name: archived
    type: Boolean
    options: {}
    path: ""
    id: wEuejG
  - name: area
    type: Select
    options:
      valuesList: {}
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages("#area").map(p => p.file.name)
    path: ""
    id: h6oegn
  - name: resource
    type: Select
    options:
      valuesList: {}
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages("#resource").map(p => p.file.name)
    path: ""
    id: RcOSg2
  - name: project
    type: Select
    options:
      valuesList: {}
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages("#project").map(p => p.file.name)
    path: ""
    id: PaUl2c
Created: 2023-12-08 12:44:29
Updated: 2023-12-10 11:17:30
---
