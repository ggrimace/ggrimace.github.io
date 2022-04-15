---
title : TEMPLATE FILE 1
notetype : feed
date : 15-04-2021
---

# Template Configuration

## Documentation 
### Retrieves Date
Today's Date :  <% tp.date.now("YYYY-MM-DD") %>
Day of the week, Today's Date : <% tp.date.now("YYYY-MM
-DD, dddd") %>

### File Title
File Title : <% tp.file.title %>
Date + File Title : <% tp.date.now("YYYY-MM-DD", tp.file.title) %>


# YAML FRONTMATTER

Retrive Frontmatter 
<% tp.frontmatter.title %>
<% tp.frontmatter.notetype %>
<% tp.frontmatter.date %>

# Jekyll bullshit time
