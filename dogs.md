---
layout: page
title: Dogs
permalink: /dogs/
---

This page needs to contain some interesting information about the dogs.

* dogs like to follow you
* dogs make lots of noise
* dogs like jump and run

<div class="dogs">
  {% for dog in site.dogs limit:10 %}
    <article class="dog">
      <a href="{{ site.baseurl }}{{ dog.url }}">{{ dog.title }}</a>
    </article>
  {% endfor %}
</div>
