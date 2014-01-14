---
layout: default
title: agronomyinfo.tk
---
<div id="home">
[![logo](/favicon.ico)](http://agronomyinfo.tk/)
<h2>{{ page.title }}</h2>
<p>最新文章</p>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
