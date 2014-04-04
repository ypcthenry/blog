---
layout: default
title: 肆意雪's Blog—— Yesterday, you said tomorrow.
---
<center><h3>{{ page.title }}</h3></center>  


<span style="margin-left:150px;margin-right:150px">How to stop time: kiss.How to travel in time: **read**.How to feel time: **write**. </span> 

      
<div style="margin-left:150px;margin-right:150px"><hr/>
<div>
<p>最新文章</p>
<div style="height:360px;">
<ul>
{% for post in site.posts %}
<li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul> 
</div> 
</div>  

<hr/>
<div style="margin-left:0px;margin-right:0px">
<div style="float:left"><a href="http://www.danasoft.com"><img src="http://www.danasoft.com/vipersig.jpg" border="0"></a></div>
<div style="float:right;margin-right:200px">Copyright &copy; 2014 Ypchenry ,Hosted by <a href="https://github.com" style="text-decoration:none">GitHub</a></div>
</div>
</div>


