---
layout: page
title: 
tagline: Simple is a good thing.
---
{% include JB/setup %}

孙宝明，目前工作于[敦煌网](http://www.dhgate.com), 担任系统架构经理。  
经常出没于北京地铁, 故作思考状，其实是人实在多，实在什么也干不了。发个呆而矣。  
热爱简单生活，喜欢折腾，刷过路由器，拆过mac本，修过hifi功放。最近准备弄家庭NAS以及修好被孩子弄坏的收音机天线。

<p> <a class="btn" href="/about.html">&gt;关于我</a> </p>
<p> <a class="btn" href="/projects.html">&gt;我参加过的项目</a> </p>
<p> <a class="btn" href="http://www.kuaipan.cn/file/id_53225996396011675.htm">&gt;我的完整简历PDF下载</a> </p> 

<p>我的涂鸦文章，TODO中..</p>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

