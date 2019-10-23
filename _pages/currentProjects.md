---
layout: archive
title: "Current Projects - Chester Conservation Biology Research Group"
permalink: /currentProjects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Description of current projects

{% for post in site.currentProjects reversed %}
  {% include archive-single.html %}
{% endfor %}
