---
layout: default
title: 肆意雪's Blog—— Yesterday, you said tomorrow.
---
<center><h2>{{ page.title }}</h2></center>  


&copy;How to stop time: kiss.How to travel in time: **read**.How to feel time: **write**.  

      
* * * 

###最新文章###
<div style="height:400px;width:800px;clear:both;">
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul> 
</div>   

* * *  


