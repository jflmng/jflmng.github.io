---
layout: single
title: News
permalink: /news/
redirect_from:
  - /posts/
---

{% for post in site.posts %}
<article class="archive__item">
  <h2 class="archive__item-title"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
  <p class="page__meta"><i class="far fa-calendar-alt"></i> {{ post.date | date: "%-d %B %Y" }}</p>
  <p class="archive__item-excerpt">{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
</article>
{% endfor %}
