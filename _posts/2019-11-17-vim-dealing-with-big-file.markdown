---
title:  "Vim - dealing with big files"
date:   2019-11-17 09:04:23
categories: [vim big_file]
tags: [jekyll]
---
Vim is my daily driver in terms of editing file. Although I mostly use the "vanilla" vim without installing any plugin, Vim gets very slow when opening a very big file.     
  
To deal with this issue, I've found the option -u in vim.  

``` ruby
$  vim -u "NONE" very_big_file.csv

```

By giving the name "NONE" all initializations will be skipped. 
