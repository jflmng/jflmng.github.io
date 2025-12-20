---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
---

## Welcome

I am a **Senior Lecturer (Associate Professor) in Intelligent Control Systems** at Loughborough University's Wolfson School of Mechanical, Electrical and Manufacturing Engineering.

My research focuses on **Optimal Control**, **Model Predictive Control (MPC)**, and **Machine Learning** for constrained and uncertain systems, with applications in **autonomous vehicles**, **motorcycles**, and **renewable energy**.

### Research Highlights
*   **Safe Autonomy**: Developing AI methods to automatically design MPC for safe motion control of autonomous systems.
*   **Holly Health**: Partnering with industry to create AI-driven apps for managing chronic health conditions.

[Read more about my research](/research/){: .btn .btn--primary}

### Latest News
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <span class="archive__item-caption">({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>
