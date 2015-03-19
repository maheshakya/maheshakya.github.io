---
layout: page
title: "LSH Forests for Approximate Nearest Neighbor Search - GSoC 2014 with scikit-learn"
description: ""
---
<div id="home">
  <ul class="posts">
	{% for post in site.posts %}
	  {% if post.category contains 'GSoC' %}
	      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
	  {% endif %}
	{% endfor %}
  </ul>
</div>