---
layout: post
title: "Github"
date: 2015-09-15 03:21:35
image: '/assets/img/'
description: 'Host The Website on Github'
tags:
- jekyll
- Github
categories:
- Jekyll 
twitter_text: 'Host The Website on Github.'
---

Github offers free hosting for jekyll websites. All you need just a few steps and your website will be online.
User and organization pages live in a special GitHub repository dedicated to only the GitHub Pages files. This repository must be named after the account name. I chose the name "Web-Development" for this project, and I made it public. In order to host our website on Github we need to create a branch called GH-pages. By the way, I clone the repository on my Windows 10 platform, and the steps I am explaining are all on Github app on Windows. Next we should change the default branch to gh-pages. Now the website is ready to be hosted on Github. Now all we need is to upload the website files on the repository, commit them, and synchronize.


{% highlight ruby %}


{% endhighlight %}

Now let's see some important configrations, in _config.ms we have to make sure that our first line is "markdown: redcarpet" whcih tells the browser that we are using markdown language. Also we need to set the url on the name of our repository. It's may worth to know that you can exclude some files from running with the project by using the commond "exclude: ['filename.xxx']""

For more information Check out these links 
http://jekyllrb.com/
https://www.youtube.com/watch?v=C6H2U_ZA99o

[jekyll-gh]: https://github.com/Web-Development
[jekyll]:    http://jekyllrb.com