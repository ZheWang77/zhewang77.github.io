---
layout: archive
title: "Awards"
permalink: /portfolio/
author_profile: true
---

Some award certificates are presented.

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single2.html %}
{% endfor %}
