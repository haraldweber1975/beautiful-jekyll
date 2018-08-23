---
layout: post
title: Markdown Test
subtitle: Each post can have a subtitle
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
tags: [markdown, test]
---
Experimenting with markdown in this post.

[This Link](https://kramdown.gettalong.org/quickref.html) provides a quick reference to Kramdown, which is the markdown dialect used by jekyll.

## Text formating
Bold Text
**The quick brown fox jumps over the lazy dog**

Italic Text

_The quick brown fox jumps over the lazy dog_

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


Embedding a remote picture

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

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

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Abbreviations
Let's see if the abbreviation for HTML will work

*[HTML]:Hyper Text Markup Language
