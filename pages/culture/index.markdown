---
layout: page
title: "Culture"
description: ""
---
<div id="home">
  <ul class="posts">
	{% for post in site.posts %}
	  {% if post.category contains 'culture' %}
	      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	  {% endif %}
	{% endfor %}
  </ul>
</div>
