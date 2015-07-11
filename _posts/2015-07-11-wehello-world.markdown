---
layout: post
title:  "Hello World!"
date:   2015-07-11 00:54:36
categories: jekyll jenkins github
---
So... I built a blog. This is it. Enjoy.

If you want to see the source, you can find it at the usual [Github]: 
https://github.com/bitbyt3r/bitbyt3r-website

As you can see there, this site is using Jekyll. I added a webhook 
that allows me to update this blog by pushing to Github, which then 
fires off our local Jenkins server to pull the repo and run
{% highlight bash %}Jekyll build{% endhighlight %}.
If that succeeds, the result is pushed to my webserver running under systemd-nspawn.

Hopefully, with this level of convenience, I might actually update the 
darn thing. Who am I kidding. See y'all in 2 years to dish out 
apologies and sad excuses.
