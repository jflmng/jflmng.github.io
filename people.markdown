---
layout: single
title: People
permalink: /people/
classes: wide
redirect_from:
  - /group/
---

## Group lead

<div class="people-grid">
{% for p in site.data.people.lead %}{% include person-card.html person=p %}{% endfor %}
</div>

## Research staff

<div class="people-grid">
{% for p in site.data.people.researchers %}{% include person-card.html person=p %}{% endfor %}
</div>

## PhD students

<div class="people-grid">
{% for p in site.data.people.students %}{% include person-card.html person=p %}{% endfor %}
</div>

{% if site.data.people.alumni.size > 0 %}
## Alumni

<ul>
{% for p in site.data.people.alumni %}
  <li><strong>{{ p.name }}</strong>, {{ p.role }} ({{ p.years }}){% if p.now %}. Now: {{ p.now }}{% endif %}</li>
{% endfor %}
</ul>
{% endif %}

Interested in joining us? See [open positions](/join/).
