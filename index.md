---
layout: default
title: 肆意雪's Blog—— Yesterday, you said tomorrow.
---
<center><h3>{{ page.title }}</h3></center>  


&copy;How to stop time: kiss.How to travel in time: **read**.How to feel time: **write**.  

      
* * * 
<div style="margin-left:40px;margin-right:40px">
<p>最新文章</p>
<div style="height:360px;width:1000px;clear:both;">
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul> 
</div> 
</div>  

* * *  
<div style="margin-left:150px;margin-right:300px">
<div style="float:left"><a href="http://www.danasoft.com"><img src="http://www.danasoft.com/vipersig.jpg" border="0"></a></div>
<div style="float:right">Copyright @ 2014 Ypchenry ,Hosted by <a href="https://github.com">GitHub</a></div>
</div>


