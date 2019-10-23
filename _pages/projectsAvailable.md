---
layout: archive
title: "Projects Available - Chester Conservation Biology Research Group"
permalink: /availableProjects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Description of available projects

{% for post in site.availableProjects reversed %}
  {% include archive-single.html %}
{% endfor %}
