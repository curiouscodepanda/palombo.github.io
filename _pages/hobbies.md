---
layout: archive
title: "Hobbies"
permalink: /hobbies/
author_profile: true
---

You can find articles on my hobbies below

{% include base_path %}

{% for post in site.hobbies reversed %}
  {% include archive-single.html %}
{% endfor %}
