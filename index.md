---
layout: default
title: 肆意雪的Blog----Yesterday, you said tomorrow.
---
<center><h2>{{ page.title }}</h2></center>
<span style="float:right;">How to stop time: kiss.</span>
<span style="float:right;">How to travel in time: read.</span>
<span style="float:right;">How to feel time: </span>**write**.
<span style="float:right;">How to waste time: social media.</span>
<p><h4>最新文章</h4></p>
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>