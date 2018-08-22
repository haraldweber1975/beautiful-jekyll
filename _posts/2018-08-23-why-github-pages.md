---
layout: post
published: true
title: Why github pages?
subtitle: reaching the goal with some obstacles
date: '2018-08-23'
---
This post will tell you why and how I started to blog on GitHub Pages

##Motivation
I'm rarely posting anything useful and my main motivation is (or was?) to simply try out new things. I'm mainly interested in the backend and the workflow of all those blogging tools out there.

I played with several free CMS systems like [Drupal](https://www.drupal.org), [Yoomla](https://www.joomla.org), [Movable type](https://movabletype.com), etc...
I always ended up impementing the site + theme + "hello world" article... and no more content.

##Where I come from
In my world a blog was made up of a webserver, database, content.
Setting up a [wordpress](http://www.wordpress.com) blog on your own rootserver is fun, but you need some background know-how and I always lost a lot of time in searching for a "beautiful" theme that fits my need - although these were never ever defined anywhere.
Running your own root server is also time-consuming and I see no reason why to spend time and money on this.

##New approach
Recently I managed to have some free time in the evenings. This is chellenging as I have 4 kids and a dog - not to forget my wife of course ;)

Idea was to create something useful with Wordpress, but the amount of ads on a free wordpress blog is really amazing!

Googling for a free hosting withoug ads, I discovered GitHub Pages.
I was considering Github mainly as a CVS system for Programmers - and it is.
But Github Pages offers some nice Static website generator - [Jekyll](http://jekyllrb.com).

##Requirements
To summarize I'm looking for a 
1. Free hosting & **No Ads**
3. Bring your **own domain name**
4. **Easy** to maintain
5. Write via Browser / console / mobile device
6. No database to worry about in case of "moving on"

##Yourney till I found a proper workflow
I first thought you need to utilize git (the command line tool for sync code with GitHub) and it was fun to learn how it works. It's not a very convenient way to maintain a blog.

I then installed Jekyll locally on my PC as I thought this is required to push the generated pages to GitHub.

Next I was looking for a nice theme. With wordpress it's quite simple to change the theme of your blog - in Jekyll it's not. Or let's say I didn't find an easy "on-click" solution.

##Current simplified Setup
Simplifying things is key to keep you motivated - in my opinion.
So this is how my blog is currently set up.

1. Create github account on github.com
2. Clone the repository of your favorite theme.  
I like this theme: [daattali/beautiful-jekyll](https://github.com/daattali/beautiful-jekyll)
3. Rename your cloned repository to **<yourgitusername>.github.io**
  
That's really all you need to do to have a jekyll powered website hosted in GitHub Pages.
{: .box-note}
**Note:** Your page will be reachable with a sexy url of <yourgitusername>.github.io
