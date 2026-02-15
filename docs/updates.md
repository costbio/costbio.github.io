---
layout: default
title: Updates
permalink: /updates
---

<h3 class="fw-bold border-bottom pb-2 mb-4">All Updates</h3>

<div class="updates-list">
  {% for post in site.posts %}
  <a href="{{ post.url }}" class="update-item">
    <span class="update-title">{{ post.title }}</span>
    <span class="update-date">{{ post.date | date: "%B %-d, %Y" }}</span>
  </a>
  {% endfor %}
</div>
