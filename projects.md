---
title: projects
permalink: /projects/
---


{% for pub in site.categories['publications'] %}
  {% capture currentyear %}{{pub.date | date: "%Y"}}{% endcapture %}
  {% if currentyear != year %}

## {{ currentyear }}
    {% capture year %}{{currentyear}}{% endcapture %}

  {% endif %}
