---
layout: page
title: "Life and Nature"
description: ""
---
<div id="home">
  <ul class="posts">
	{% for post in site.posts %}
	  {% if post.category contains 'life_and_nature' %}
	      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	  {% endif %}
	{% endfor %}
  </ul>
</div>
