---
layout: single
author_profile: true
title: Research Group
permalink: /group/
---

## Postdoctoral Researchers and Fellows

{% for p in site.data.group.staff %}
<div class="notice--info">
  <h4>{% if p.url %}<a href="{{ p.url }}">{{ p.name }}</a>{% else %}{{ p.name }}{% endif %}</h4>
  <p><strong>{{ p.role }}</strong>{% if p.topic %}<br>{{ p.topic }}{% endif %}{% if p.email %}<br><a href="mailto:{{ p.email }}">{{ p.email }}</a>{% endif %}</p>
</div>
{% endfor %}

## PhD Students

{% for p in site.data.group.students %}
<div class="notice--info">
  <h4>{% if p.url %}<a href="{{ p.url }}">{{ p.name }}</a>{% else %}{{ p.name }}{% endif %}</h4>
  <p><strong>{{ p.role }}</strong>{% if p.topic %}<br>{{ p.topic }}{% endif %}{% if p.email %}<br><a href="mailto:{{ p.email }}">{{ p.email }}</a>{% endif %}</p>
</div>
{% endfor %}
