---
layout: post
title: "Jekyll Layout"
date: 2015-09-29 03:21:35
image: '/assets/img/'
description: 'Markdoun & Textile'
tags:
- jekyll
categories:
- Jekyll 
twitter_text: 'How to install Jekyll.'
---

##Intro
It's a good idea to take a look on at the format that jekyll understands, because this is what we are going to be doing the most once we finish developing our website and what we are going to do is publishing content.
As I mentioned in previous blogs Jekyll supports HTML, Markdown, and textile. Therefor in this blog I will give a brief look at markdown and textile format.   
# Markdown & Textile
markdown and textile are both markup languages, they easier to write, read, and edit for a human prespective.
markdown can have both file extention, full ".markdown" and short ".md" 

## Markdown  
Let me give the basic and most used features for markdown  
- To write a header all you have to do is type # before your header separated by a space. one # sign will create an h1 tag, two # signs will create an h2 tag, and so on.  
- To make a text *italic* you put stars around it.  
- To make a text **bold** you put double stars around it.  
- To create link all you have to do is wrap it the text you want to link you your link in square brackets, and the link url after it in rounded brackets.  
- For a list you just put a star in fort of each item.  
- For image, we put the explaination point followed by square brackets with alternative text followed by round brackets with the path of the image.  

## Textile  
in textile all you need to do is to type the name of the tag with dot at the end and the content separated with a space.  
- To write a header all you have to do is type h and the number of the header tage, for example h1. Header.  
- To make a text *italic* you wrape it with double underline signs __  
- To make a text **bold** you put double stars around it.  
- To create link all you have to do is wrap it the text you want to link with double qoute followed by colin and the url you want to link to  
- For a list you jsut put a star in fort of each item.  

{% highlight ruby %}
##=>how do jekyll layouts work?

the default layout of jekyll uses sleek to request the content from other files instead of the default HTML layout. this layout generates foundation elements of every page. If you open the default layout file you can see for example the liquid include tag that grabs the content of head.html and inserts it in the place itself. 
{% endhighlight %}




For more information Check out these links 



[jekyll-gh]: https://github.com/Web-Development
[jekyll]:    http://jekyllrb.com