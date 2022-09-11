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
    - /de/language/
    - /de/languages/
    - /la/language/
    - /la/languages/
---
{% include base_path %}

{% for post in site.language_stuff %}
  {% include archive-single-language.html %}
{% endfor %}

{% for post in site.language_stuff %}
  {% include archive-single.html %}
{% endfor %}
