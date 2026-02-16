---
date: <% tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm") %>
tags:
  - Daily
cssclasses:
  - daily
  - image-borders
  - hide-properties
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "YYYYMMDD").toLowerCase() %>
---
# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "YYYYMMDD") %>
***
### Journal

