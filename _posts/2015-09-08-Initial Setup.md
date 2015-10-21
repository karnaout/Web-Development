---
layout: post
title: "Installing Jekyll"
date: 2015-09-08 03:21:35
image: '/assets/img/'
description: 'How to install jekyll on Localhost server'
tags:
- jekyll
categories:
- Jekyll 
twitter_text: 'How to install Jekyll.'
---

##Intro
Jekyll can work fine on any platform, but since Jekyll is a parsing engine bundled as a ruby gem, it's easir to deal with it using Linux or Mac system. The following explanations assume that we work on Ubuntu 14. Now, after platforms, let's see how jekyll works. 
To build a website using jekyll. First you make a template, you make content then you run jekyll and you get the website. After getting the website you can just upload it to any basic server and the website works awsomely. 

##The Requirements are
Ruby (including development headers, v1.9.3 or above for Jekyll 2 and v2 or above for Jekyll 3)
RubyGems
Linux, Unix, or Mac OS X
NodeJS, or another JavaScript runtime (Jekyll 2 and earlier, for CoffeeScript support).
Python (Jekyll 2 and earlier)

Now, Let's start building the website. Open the terminal, now the first thing we need to do is install jekyll by typing "sudu gem install jekyll". The next step is to start new jekyll project by typing "Jekyll new my-website-name". Pretty much that is all, now if you open your project folder then type "jekyll serve" you see jekyll is running and working. To check that out you just can type the name of your local server, which mostly is localhost:4000, in your browser.


{% highlight ruby %}

~ $ gem install jekyll
~ $ jekyll new my-awesome-site
~ $ cd my-site
#=> ~/my-site $ jekyll serve
#=> Now browse to http://localhost:4000 
{% endhighlight %}

Now the next step is to edit the content and give values to some variables. The most important configurations are in a file called _config.yml
there are a lot of documentations on jekyll website can walk you through all steps you need. Now beside configurations there are too many files we need to get ourselves familiar with in order to better understanding to the way jekyll works. 


For more information Check out these links 
http://jekyllrb.com/
https://www.youtube.com/watch?v=iWowJBRMtpc


[jekyll-gh]: https://github.com/Web-Development
[jekyll]:    http://jekyllrb.com