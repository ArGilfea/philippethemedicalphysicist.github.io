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
{% for post in site.language_stuff reversed %}
  <a href="{{ post.link }}">{{ post.title }}</a>
{% endfor %}