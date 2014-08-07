---
layout: page
title: Goats
permalink: /goats/
---

This page needs to contain some interesting information aboutthe goats.

* goats like to follow you
* goats make lots of noise
* goats like to eat

<div class="goats">
  {% for goat in site.goats limit:10 %}
    <article class="goat">
      <a href="{{ site.baseurl }}{{ goat.url }}">{{ goat.title }}</a>
    </article>
  {% endfor %}
</div>
