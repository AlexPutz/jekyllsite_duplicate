---
layout: archive
title: "Articles"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "A collection of articles, thoughts and notes."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.en %}
{% if post.categories contains "articles" %}
    {% include post-grid.html %}
{% endif %}
{% endfor %}
</div><!-- /.tiles -->
