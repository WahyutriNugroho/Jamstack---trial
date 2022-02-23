---
title: My first page - Wahyutri Nugroho
layout: base.njk
---

Hello World - Wahyu

{% include "postlist.njk" %}

{% for fact in facts | randomItem %}
{% endfor %}

## Cat of the Day

<img src="{{ catpic }}" />
<!-- templateEngineOverride: njk,md -->

<!-- ## Blog Posts -->

<!-- {% for post in collections.posts %}
{{ post.data.title }}
{% endfor %} -->
