---
layout: default
title: 肆意雪的Blog----Yesterday, you said tomorrow.
---
<center><h2>{{ page.title }}</h2></center>
How to stop time: **kiss**.
How to travel in time: **read**.
How to feel time: **write**.
How to waste time: **social media**.
<p><h4>最新文章</h4></p>
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>