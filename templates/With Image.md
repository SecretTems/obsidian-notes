---
layout: post
title: <% tp.file.title %>
categories:
tags: []
date: 2026-09-06 11:13:58 +08:00
date modified: 2026-09-06 18:18:00 +08:00
image:
    path:
    alt:
---
# <% tp.file.title %>


## Section One

Content goes here...

> block quote with light bulb
{: .prompt-tip }







<% await tp.file.rename(tp.date.now("YYYY-MM-DD-") + tp.file.title.toLowerCase().replace(/\\s+/g, '-')) %>
