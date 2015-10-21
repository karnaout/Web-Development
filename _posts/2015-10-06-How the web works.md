---
layout: post
title: "Web Design Fundamentals"
date: 2015-10-06 03:21:35
image: '/assets/img/'
description: 'How the Web Works'
tags:
- jekyll
categories:
- Jekyll 
twitter_text: 'How to install Jekyll.'
---

##Intro
In web designing it's very important to understand how the web works and the processes involved in hosting, serving, and rendering web sites. By understanding the terminology and processes involved, we create more efficient sites and have a concrete understanding of why we do the things we do.

Before I move on to specific terminology I want to take a moment to examine how the web works as an overall process. If you could compare learning web design to building a house, consider this the foundation. The web can be summarized as a series of interactions between two types of systems, clients and servers. Clients are the devices are request and render your web content. Popular clients include browsers, mobile devices, screen readers, email programs and chat client. We live in an increasingly connected world and the number of clients that can access web content is growing rapidly. In fact trying to keep up with all new clients and how they access in render your content is one of the most challenging aspects of web design. Servers are applications that deliver web content or services to the clients. There’s a wide range of web servers from FTP servers, mail servers, database servers, name servers, application servers and more. They are all involved in some way in delivering the content your request or the services you need performed. 

## How the web works  
Now that we understand the client-server model the web is based on, let’s take a closer look at the process of requesting and receiving web contents. Most of us probably already understand that the browser request pages from web servers based on the links that we click or the addresses we type in the browser. As with most processes however there’s a little bit more going on behind the scenes; when your browser makes a request it uses a URL or uniform resource locator to locate the requested content this request is usually passed on to a domain name server or DNS. The DNS then translates the URL into an IP address, the browser then uses this IP address to locate the host server and send a request for the content. Now based on the file type requested several things take place next if the request is a simple HTML page the HTML text is sent to browser where it’s rendered and then presented to the user if the page contains additional request such as CSS or images these requests are presented to the server and rendered as well any client-side scripts such as JavaScript or CGI that are triggered by the document loading are also executed at this point. If the file type request it is a type that must first be processed by a web applications such as PHP, Dotnet or HTML. Then before the content is sent to the browser the page is first processed and then the appropriate data is returned to the browser to be rendered as before request such a style sheets images in client-side scripts are then executed at this is a fairly broad fairly big picture view of how the web works and the other chapters in this research all begin to discuss individual terms and functionality in web designing which will deepen the understanding of how these processes work together.  

{% highlight ruby %}
##=> Make a request -->> http://karnaout.github.io/Web-Development/
##=> Request passes to DNS
##=> Translate the URL into IP
##=> Render the request in the host server
##=> Present to the user


{% endhighlight %}




For more information Check out these links 



[jekyll-gh]: https://github.com/Web-Development
[jekyll]:    http://jekyllrb.com