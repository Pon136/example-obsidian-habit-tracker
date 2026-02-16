---
cssclasses:
  - wide
  - hide-properties
obsidianUIMode: preview
---
```base
views:
  - type: cards
    name: Cards
    filters:
      and:
        - '!note["Project Name"].isEmpty()'
        - '!file.folder.contains("Completed")'
    order:
      - Project Name
      - Description
      - End Date
    sort:
      - property: End Date
        direction: ASC
    image: note.Image
    imageAspectRatio: 0.55
    cardSize: 240
  - type: timeline-view
    name: Timeline
    filters:
      and:
        - '!note["Project Name"].isEmpty()'
    groupBy:
      property: category
      direction: ASC
    order:
      - file.name
    startField: note.Start Date
    endField: note.End Date
    contentField: note.Project Name

```

