---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

You can find my projects below:

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
