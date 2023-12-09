---
limit: 100
mapWithTag: true
icon: target
tagNames:
  - project
filesPaths: 
bookmarksGroups: 
excludes: 
extends: Action
savedViews: []
favoriteView: 
version: "2.42"
fields:
  - name: status
    type: Select
    options:
      valuesList:
        "1": ⚪
        "2": 🟢
        "3": 🔴
        "4": 🔵
        "5": ⚫
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: 82Npwz
  - name: archived
    type: Boolean
    options: {}
    path: ""
    id: oKnYrv
  - name: priority
    type: Select
    options:
      valuesList:
        "1": 🟦
        "2": 🟨
        "3": 🟥
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: WoJmls
  - name: area
    type: Select
    options:
      valuesList: {}
      sourceType: ValuesFromDVQuery
      valuesListNotePath: ""
      valuesFromDVQuery: dv.pages("#area").map(p => p.file.name)
    path: ""
    id: Vf1n6O
Created: 2023-12-08 00:35:39
Updated: 2023-12-08 15:39:53
---
