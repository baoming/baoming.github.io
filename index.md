---
layout: page
title:  
tagline: Simple is a good thing. ------做人、做事。
---
{% include JB/setup %}

孙宝明，目前工作于[敦煌网](http://www.dhgate.com), 担任基础架构部系统总监。已服役满6年+。  

热爱简单生活，喜欢折腾，长期关注开源项目和技术趋势。

`Simple is a good thing.` 是我信奉和非常喜欢的一句话，无论是做人、做事还是设计系统。大道至简。



<p> <a class="btn" href="/about.html">&gt;关于我</a> </p>
<p> <a class="btn" href="/projects.html">&gt;我参加过的项目</a> </p>
<p> <a class="btn" href="http://baoming.b0.upaiyun.com/孙宝明简历.pdf">&gt;我的完整简历PDF下载</a> </p> 

<p>我的涂鸦文章，TODO中..</p>

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

