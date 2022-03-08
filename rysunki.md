---
layout: default
title: Rysunki
permalink: /rysunki/
published: true
---

## Rysunki

<div class="posts covers-container">
  {% for post in site.categories.rysunek %}
      <div class="single-cover">
        <a href="{{ site.baseurl }}{{ post.url }}">
          {{ post.excerpt }}
        </a>
      </div>
  {% endfor %}
</div>
