---
layout: post
comments: true
title:  "Setting up Boost on MAC"
date:   2017-10-15 21:35:00 +0530
categories: [boost, macos, xcode]
---
I wanted Boost for programming to use some of the functionality not provided on the standard library.

So I tried the steps from the link – [Configure Boost on XCode](http://neutrofoton.github.io/blog/2016/03/27/configure-boost-c-plus-plus-on-xcode/)

It works well except that I need to perform the below action –
{% highlight bash %}
sudo chown -R $USER /usr/local/boost_1_65_1/
{% endhighlight %}

Here is my local machine setup –
Boost : 1.65.1
Mac : 10.8.5
XCode : 5.1.1 (5B1008)
