---
layout: page
title: "Collaborations"
permalink: /collaborations
---

<div class="row g-3">
  {% for collaborator in site.data.settings.collaborators %}
  <div class="col-md-6 col-xl-4">
    {% if collaborator.url %}
    <a href="{{ collaborator.url }}" class="update-item h-100" target="_blank">
    {% else %}
    <div class="update-item h-100">
    {% endif %}
      <span class="update-title">{{ collaborator.name }}</span>
      <span class="update-date">{{ collaborator.institution }}{% if collaborator.country %}, {{ collaborator.country }}{% endif %}</span>
    {% if collaborator.url %}</a>{% else %}</div>{% endif %}
  </div>
  {% endfor %}
</div>
