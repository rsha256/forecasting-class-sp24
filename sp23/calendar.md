---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar

{% for module in site.modules %}
  {% if module.path contains 'sp23' %}
    {{ module }}
  {% endif %}
{% endfor %}
