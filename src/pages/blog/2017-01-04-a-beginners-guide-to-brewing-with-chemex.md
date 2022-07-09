---
templateKey: blog-post
title: Simple search solution in Javascript
date: 2017-01-04T15:04:10.000Z
description: I tried out a few different JavaScript search options and found
  that while most worked great to add search functionality in JS, some most were
  lacking in features (or more opinionated than I cared for) for my needs.
featuredpost: false
featuredimage: /img/chemex.jpg
tags:
  - brewing
  - chemex
---
![chemex](/img/chemex.jpg)

I tested Fuse.js and this was a win for my use case. It allowed me to easily set an index from the data that I fetched from my API and query for data which is returned in the **same shape** as my initial data.

## Setting up my index

… code block here