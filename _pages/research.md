---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for research in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
