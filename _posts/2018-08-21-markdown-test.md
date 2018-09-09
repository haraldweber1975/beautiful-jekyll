---
title: Markdown Test
subtitle: my Markdown cheat sheet
date: 2018-08-21 00:00:00 +02:00
tags:
- markdown
- test
layout: post
image: "/img/markdown.jpg"
bigimg: "/img/under_construction.jpg"
---
Experimenting with markdown in this post.


## Table of contents
{:.no_toc}

1. TOC
{:toc}

##cSome usefull links
[This Link](https://kramdown.gettalong.org/quickref.html) provides a quick reference to Kramdown, which is the markdown dialect used by jekyll.

## Text formating
Bold Text  
**The quick brown fox jumps over the lazy dog**

Italic Text  
_The quick brown fox jumps over the lazy dog_

## Tables

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


## Embedding a remote picture
![Jekyll](http://lioon.net/assets/images/jekyll-logo-light-transparent.png)


## Code chunks
Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Notification Box

{: .box-note}
**Note:** This is a notification box.

## Warning Box

{: .box-warning}
**Warning:** This is a warning box.

###Error Box

{: .box-error}
**Error:** This is an error box.

## Abbreviations
Let's see if the abbreviation for HTML will work. Simply hover over the HTML text.

*[HTML]:Hyper Text Markup Language


