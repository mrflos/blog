---
layout: archive
permalink: /videos/
title: "Vidéos"
image:
  feature: featured-videos.jpg
---

<div class="tiles">
{% for post in site.categories.videos %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
