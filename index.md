---
layout: page
title: Welcome
tagline: on my github page
---
{% include JB/setup %}

The page is about my dev projects available on github. 

At the moment, you can find the documentation for : 

* [Wifi-rc-car](http://jbtheou.github.io/wifi-rc-car)

And some pages about technicals ideas : 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

