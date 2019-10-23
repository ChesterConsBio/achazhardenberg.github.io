---
layout: archive
title: "Current Group Members - Chester Conservation Biology Research Group"
permalink: /groupMembers/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profiles of current group members

{% for post in site.groupMembers reversed %}
  {% include archive-single.html %}
{% endfor %}
