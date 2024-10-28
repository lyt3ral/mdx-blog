---
author: Sai Sabarish
pubDatetime: 2024-10-28T14:10:01.000+05:30
modDatetime: 
title: Vim Part II
featured: true
draft: false
tags:
  - vim
  - productivity 
description: Searching in Vim
---

There are several ways to search for text, which can be accessed from normal mode:

### Forward Searching (/)
1. / = allows us to perform a forward search
2. n = moves to next occurrence of word
3. N = moves to previous occurence of word
4. // = repeats the previous search

### Backward Searching (?)
1. ? = allows us to perform a backward search
2. n = moves to previous occurrence of word
3. N = moves to next occurrence of word
4. ?? = repeats the previous search

### Full Word Searching
1. `*` = searches full word in forward direction
2. `#` = searches full word in backward direction

### Find and Replace Syntax
```:%s/find/replace/options```

#### Options
1. g - global replace
2. i - case insensitive
3. c - prompt before replacing
