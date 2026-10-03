---
layout: splash
title: "Intelligent Control Group"
header:
  overlay_color: "#1f3a5f"
  # TODO: replace with a wide group/lab photo (about 1600x500px), e.g.
  # overlay_image: /assets/images/hero.jpg
  # overlay_filter: 0.5
  actions:
    - label: "Our research"
      url: /research/
    - label: "Join us"
      url: /join/
excerpt: >-
  We develop control and learning methods that let autonomous systems act optimally
  and safely under uncertainty, from self-driving vehicles and motorcycles to
  offshore wind and digital health.<br><small>Wolfson School of Mechanical, Electrical and Manufacturing Engineering, Loughborough University</small>
feature_row:
  - title: "Safe predictive control"
    excerpt: "Model predictive control that keeps uncertain, constrained systems safe, with guarantees that hold up in the real world."
    url: /research/#safe-predictive-control
    btn_label: "Read more"
    btn_class: "btn--primary"
  - title: "Learning-enabled control"
    excerpt: "Combining reinforcement learning with differentiable MPC so safe controllers can be designed automatically from data."
    url: /research/#learning-enabled-control
    btn_label: "Read more"
    btn_class: "btn--primary"
  - title: "AI for health and behaviour"
    excerpt: "Adaptive, personalised interventions that help people manage long-term health conditions."
    url: /research/#ai-for-health-and-behaviour
    btn_label: "Read more"
    btn_class: "btn--primary"
---

{% include feature_row %}

## Latest news

<ul>
  {% for post in site.posts limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span class="archive__item-caption">({{ post.date | date: "%-d %B %Y" }})</span></li>
  {% endfor %}
</ul>

[All news](/news/){: .btn .btn--inverse}

## Funders and partners

<div class="partners">
{% for p in site.data.partners %}
  {% if p.url %}<a href="{{ p.url }}">{% endif %}{% if p.logo %}<img src="{{ p.logo | relative_url }}" alt="{{ p.name }}">{% else %}{{ p.name }}{% endif %}{% if p.url %}</a>{% endif %}
{% endfor %}
</div>
