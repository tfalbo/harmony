---
layout: page
title: Archive
permalink: /archive/
link: archive
lang: en
---
<div class="page-content wc-container">
  <h1>Blog Archive</h1>
  {% assign posts=site.posts | where:"lang", page.lang %}   
  {% for post in posts %}
  	{% capture currentyear %}{{post.date | date: "%Y"}}{% endcapture %}
  	{% if currentyear != year %}
    	{% unless forloop.first %}</ul>{% endunless %}
    		<h5>{{ currentyear }}</h5>
    		<ul class="posts">
    		{% capture year %}{{currentyear}}{% endcapture %} 
  		{% endif %}
    <li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endfor %}
</div>
