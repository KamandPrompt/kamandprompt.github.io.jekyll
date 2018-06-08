---
layout: archive
permalink: /blog/
title: "Blog"
excerpt: "KamandPrompt - Blog"
---

<h3 class="archive__subtitle">All Posts</h3>

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
