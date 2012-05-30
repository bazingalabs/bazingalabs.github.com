---
layout: page
title : Tutorials
header : List of tutorials
group: navigation
---
{% include JB/setup %}

<ul>
  {% assign pages_list = site.pages %}
  {% assign group = 'tutorials' %}
  {% include JB/pages_list %}
</ul>