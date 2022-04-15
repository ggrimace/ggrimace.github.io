---
title : TEMPLATE FILE 1
notetype : feed
date : 15-04-2021
---

# Template Configuration

## Documentation 
### Retrieves Date
Today's Date :  <% tp.date.now("MM-DD-YYYY") %>
Day of the week, Today's Date : <% tp.date.now("dddd, MM-DD-YYYY") %>

### File Title
File Title : <% tp.file.title %>
Date + File Title : <% tp.date.now("MM-DD-YYYY", tp.file.title) %>


