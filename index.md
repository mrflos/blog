---
layout: archive
permalink: /
title: "Dernières publications"
image:
  feature: featured-home.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
