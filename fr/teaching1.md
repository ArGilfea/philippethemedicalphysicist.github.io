---
layout: archive
title: "Enseignement"
permalink: //teaching/
author_profile: true
lang: fr
---
{% include base_path %}

{% for post in site.teaching_fr reversed %}
  {% include archive-single.html %}
{% endfor %}