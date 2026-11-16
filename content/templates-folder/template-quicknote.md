---
topic: references
date: "{{date}}"
idea:
tags:
  - studies
---

<%"---"%>
<%*" <!-- Statuses: To Read, Reading, Read, To Read Again, References --> "%>
status: To Read
title: "{{title}}"
subtitle: "{{subtitle}}"
description: "{{description}}"
categories: [{{category}}]
authors: [{{author}}]
published_on: {{publishDate}}
publisher: {{publisher}}
pages: {{totalPage}}
isbn: {{isbn10}}
cover: {{coverUrl}}
local_cover: {{localCoverImage}}
link: 
tags:
- book_notes
- books
- summaries
<%"---"%>

# <% tp.file.title %>
- Author(s): {{author}}
- Link: 

![[{{localCoverImage}}|200]]

# Brief description


# Key quotes
> ...

# Key ideas
...

# Chapter 1: ...
...

## References
- 
You can of course customize it as you wish. Note that all the {{...}} blocks are specific to the Book Search plugin. You can find the full list of supported variables here.

Also, notice that I have decided to use the following values for the status property:

To Read
Reading
Read
To Read Again
References