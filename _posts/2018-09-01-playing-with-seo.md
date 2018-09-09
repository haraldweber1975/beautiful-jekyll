---

title: Playing with SEO
subtitle: Search Engine Optimisation is the key to make your site discoverable for people 
layout: post
image: "/img/seo.png"
published: true
tags:
- seo

---
In this post I'll sharae the approach, facts and links I'm using to optimize this site for .

## Let's take a quick q/a approach:

**Q:** How do people browser the web?  
**A:** by using **search engines** - in most cases "Google"

**Q:** How do these Search engines find my site?  
**A:** You have to offer something that is **unique**. 

**Q:** Ok - let's say I have something unique like a name + city I live in - how will people find me?  
**A:** You can usually **register** your site with most sear engine operators.
 Your site will then appear in their search index

**Q:** How will this help if my website ranks on place 100+ in the search results when somebody searches for me?  
**A:** **NOT AT ALL** as most people will not even scroll down or switch to the 2nd page of search results.

**Q:** O.k. got it - so how can I have a **good ranking** in search results on the **most used search engines** for this very unique thing that I can offer?  
**A:** It depends :D

This little game brings you to the __key question__
1. What are the **top search engines** 
2. What makes your site **unique** on the internet?
3. How can you improve your websites ranking when people search for **you**

## 1. Let's investigate about the top search sites
Check [Alexa topsites](https://www.alexa.com/topsites) and you´ll have an idea about the top sites on the planet.
And guess what - all major search engines I knew are in the top 10 list.

I decided that I want to optimise my site for Google, Bing and Duckduckgo

## 2. Now bring some SEO to your site to make it unique
I had to add the text 

<!-- {% raw %} -->
  ```liquid
  {% seo %}
  ```
<!-- {% endraw %} -->

right before the <HEAD> tag in the file _includes/head.html of my template.

## 3. Register your site on Google, Bing etc.

Use these links to register your site with some of the largest search engines on the planet.
The process will differ from site to site, but in most cases you have to have access to your domain configuration

- [Google Search Sitemap](https://search.google.com/search-console/sitemaps/)
- [Bing Webmaster Sitemaps](https:/www.bing.com/webmaster/configure/sitemaps/)
- [Google analytics](https://analytics.google.com/)


