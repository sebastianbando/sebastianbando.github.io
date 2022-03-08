---
layout: default
title: Wiersze
permalink: /wiersze/
published: true
---

## Wiersze

<div class="posts">
  {% for post in site.categories.wiersz %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>