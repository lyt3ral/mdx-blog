---
author: Sai Sabarish 
pubDatetime: 2024-10-27T12:50:59.000+05:30
modDatetime: 
title: Vim Part I
featured: false
draft: true
tags:
  - vim
  - productivity
description: A foray into learning Vim 
---

### Why use Vim? (gaslighting myself to believe this is worth it)

- super fast
- incredibly configurable
- time savings by not switching to a mouse 🐁
- here to stay

### Basic Vim Mode Switching

i = enter insert at the cursor beginning
I = enter insert at the line beginning
o = enter insert at the line after the cursor
O = enter insrert at the line before the cursor
a = enter insert after the cursor current position
A = enter insert at the end of the line
C = delete from the cursor to the end of the line and enter insert`

Esc = enter normal mode
NOTE: you would want to remap this to something else like jj
ctrl + [ = enter normal mode (the better way)

### Moving Around

```
    k
    ^
h <   > l
    v
    j
```

There are many ways to move around sentences with w, b, e
Now lowercase letters will consider punctuation ie ,.!?;: as words
The uppercase letters can be used to skip all that

w = Forward to the beginning of the word
W = Forward to beginning of the WORD
b = Backward to the beginning of the word
B = Backward to the beginning of the WORD
e = Forward to the end of the word
E = Forward to the end of the WORD

NOTE: It is reccomended to disable arrow keys in your vimrc file
