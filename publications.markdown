---
layout: single
title: Publications
permalink: /publications/
classes: wide
---

Publications from the group are listed below. For citation counts and the most
up-to-date list, see [Google Scholar](https://scholar.google.com/citations?user=qXhzsAMAAAAJ).

{% assign pub_years = site.data.citations | map: "Year" | uniq | sort | reverse %}
{% for y in pub_years %}
## {{ y }}

{% include publications year=y link=true %}
{% endfor %}
