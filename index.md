---
layout: default
title: 肆意雪的Blog----Yesterday, you said tomorrow.
---
<center><h2>{{ page.title }}</h2></center>
> &copy;How to stop time: kiss.How to travel in time: **read**.How to feel time: **write**.How to waste time: social media.       
###最新文章###
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
