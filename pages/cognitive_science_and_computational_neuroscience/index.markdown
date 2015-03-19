---
layout: page
title: "Cognitive Science and Computational Neuroscience"
description: ""
---
<div id="home">
  <ul class="posts">
	{% for post in site.posts %}
	  {% if post.category contains 'cognitive_and_neuroscience' %}
	      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	  {% endif %}
	{% endfor %}
  </ul>
</div>
