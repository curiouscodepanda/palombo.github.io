---
layout: archive
title: "Life Articles"
permalink: /main/
author_profile: true
---

You can find my only article so far below:
[Article on Awareness](https://palombo.life/main/awareness)

{% include base_path %}

{% for post in site.big-questions reversed %}
  {% include archive-single.html %}
{% endfor %}
