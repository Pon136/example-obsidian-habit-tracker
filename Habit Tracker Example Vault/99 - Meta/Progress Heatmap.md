---
cssclasses:
  - wide
obsidianUIMode: live
obsidianEditingMode: source
---
### All Progress
```base
views:
  - type: heatmap-calendar
    name: All Tasks Heatmap
    filters:
      and:
        - file.inFolder("06 - Daily")
        - file.hasTag("Task")
    order:
      - file.name
    imageProperty: note.Image
    dateProperty: file.name
    trackProperty: note.tags
    showDayLabels: true
    showYearLabels: false
    showLegend: false
    shape: rounded
    reverseColors: false
    colorScheme: primary
    viewMode: week-grid
    customColors: "#050512, #7D6FBB"
    trackType: number

```
### Writing
```base
views:
  - type: heatmap-calendar
    name: Writing Heatmap
    filters:
      and:
        - file.inFolder("06 - Daily")
        - file.hasTag("Task/Writing")
    order:
      - file.name
    imageProperty: note.Image
    dateProperty: file.name
    trackProperty: note.tags
    showDayLabels: true
    showYearLabels: false
    showLegend: false
    shape: rounded
    reverseColors: false
    colorScheme: primary
    viewMode: week-grid
    customColors: "#050512, #e22c3c"
    trackType: number

```
### Passion Project
```base
views:
  - type: heatmap-calendar
    name: Passion Project Heatmap
    filters:
      and:
        - file.inFolder("06 - Daily")
        - file.hasTag("Task/PassionProject")
    order:
      - file.name
    imageProperty: note.Image
    dateProperty: file.name
    trackProperty: note.tags
    showDayLabels: true
    showYearLabels: false
    showLegend: false
    shape: rounded
    reverseColors: false
    colorScheme: primary
    viewMode: week-grid
    customColors: "#050512, #52eea3"
    trackType: number

```
