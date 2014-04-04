---
layout: default
title: 肆意雪's Blog—— Yesterday, you said tomorrow.
---
<center><h3>{{ page.title }}</h3></center>  


&copy;How to stop time: kiss.How to travel in time: **read**.How to feel time: **write**.  

      
* * * 

<p>最新文章</p>
<div style="height:360px;width:800px;clear:both;">
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul> 
</div>   

* * *  

<div>
<div style="float:left"><a href="http://www.danasoft.com"><img src="http://www.danasoft.com/vipersig.jpg" border="0"></a><p><div style="font-family:Arial,sans-serif;font-size:11px;">Sign by Danasoft - <a href="http://www.danasoft.com">Get Your Sign</a></p></div></div>
<div style="float:right">Copyright&nbsp;@&nbsp;2014&nbsp;Ypchenry,Hosted by <a href="https://github.com/">GitHub</div>
</div>

