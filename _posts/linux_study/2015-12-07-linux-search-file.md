---
layout: post
category: linux_study
title: Linux: Search For A File
date: 2015-12-07
---

1. Search for a file by its file name. 
This is the most basic search you can perform using the find command. 
The command below will search for the query in the current directory and any subdirectories.

{% highlight bash %}
find -iname "filename"
{% endhighlight %}

- Using -iname instead of -name ignores the case of your query. The -name command is case-sensitive.

# Reference

**How to Find a File in Linux**

[http://www.wikihow.com/Find-a-File-in-Linux](http://www.wikihow.com/Find-a-File-in-Linux)

**How to find files in Linux using 'find'**

[http://www.codecoffee.com/tipsforlinux/articles/21.html](http://www.codecoffee.com/tipsforlinux/articles/21.html)

**35 Practical Examples of Linux Find Command**

[http://www.tecmint.com/35-practical-examples-of-linux-find-command/](http://www.tecmint.com/35-practical-examples-of-linux-find-command/)