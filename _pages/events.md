---
title: Events
permalink: /events/
layout: single
brief: Find out more about what's happening in Guernsey eSports
---
  {% for post in site.categories['upcoming-events'] %}
    {% include archive-single.html %}
  {% endfor %}
