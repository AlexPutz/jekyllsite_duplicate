---
layout: home
locale: "ru"
permalink: /
image:
  feature: pexels-photo-165509.jpeg
---

<div class="tiles">
{% for post in site.categories.en limit:8 %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

