---
layout: default
title:肆意雪's Blog—— Yesterday, you said tomorrow.
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

<div>
<div style="float:left"><a href="http://www.danasoft.com"><img src="http://www.danasoft.com/vipersig.jpg" border="0"></a><p><div style="font-family:Arial,sans-serif;font-size:11px;">Sign by Danasoft - <a href="http://www.danasoft.com">Get Your Sign</a></p></div></div>
<div style="float:right">Copyright&nbsp;&copy;&nbsp;2014&nbsp;Ypchenry,Hosted by <a href="https://github.com/">GitHub</div>
</div>

