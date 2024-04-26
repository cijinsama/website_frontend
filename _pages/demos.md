---
layout: archive
title: "Project Demo"
permalink: /demos/
author_profile: false
---

{% include base_path %}

{% for post in site.demos reversed %}
  {% include archive-single-demo.html %}
{% endfor %}
