---
layout: archive
title: "Language"
excerpt: "Personal material about languages"
permalink: /language/
author_profile: true
lang: en
redirect_from: 
    - /languages/
    - /en/language/
    - /en/languages/
    - /fr/language/
    - /fr/languages/
    - /de/language/
    - /de/languages/
    - /la/language/
    - /la/languages/
---
{% include base_path %}

{% for post in site.language_stuff reversed %}
  {% include archive-single.html %}
{% endfor %}