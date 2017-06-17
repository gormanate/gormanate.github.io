---
layout: post
title: Migration From Wordpress To Jekyll
date: 2017-06-17 11:46:17
categories: programming
---
For way too long, I've been telling myself that I would maintain a personal site, where I would provide links to projects, and occasionally write some garbage. I initially set up a Wordpress site, but it's irritating to try and customize the page. I found myself digging into documentation of how to write widgets, just generally got frustrated, and had no desire to become a WordPress expert. I could have switched over to squarespace, which would have served my purposes well, but wanted to get a little better at CSS, and control the design of my page. I already had a personal server and domain name, so figured I would move it over to a static site generator.

Side Note: I can't provide insight into the whole ecosystem of different VPS services, but I personally am using [Digital Ocean](https://www.digitalocean.com/) to host, and find their offerings to be fantastic. I am a mediocre sysadmin at best, and they provide excellent documentation to set up https, ensure your server is secure, and tons more that I still need to dig into!

There's a whole bunch of static site generators available at this point, and though I did a little reading about the costs/benefits of the different options, I ultimately went with Jekyll. Jekyll has a thriving community, a large base of people using it, and, as far as I can tell, is well documented. I know there are some complaints about the build time, but at the scale I will be operating at, I don't really care. To deploy the site to my Digital Ocean droplet, I followed the instructions [here](https://www.digitalocean.com/community/tutorials/how-to-deploy-jekyll-blogs-with-git), where I learned more about git hooks, which, as it turns out, are really useful!!

Moving from wordpress to Jekyll was way easier than I thought it might be. The process motivated me to begin the process of migrating my twitter bots from Heroku to my server, which I might talk about in a later post! If you are thinking of moving your site off of Wordpress, I would recommend it!
