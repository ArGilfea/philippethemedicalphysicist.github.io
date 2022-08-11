---
layout: archive
title: "Language"
excerpt: "Personal material about languages"
permalink: /language/
author_profile: true
lang: en
redirect_from: 
    - /languages/
---
{% include base_path %}

{% for post in site.language_stuff reversed %}
  <a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}