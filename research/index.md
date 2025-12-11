---
title: Research
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our research focuses on real-world vehicle and ship emissions, advanced and low-carbon
fuels, and heavy-duty engine testing. We combine laboratory experiments with field
campaigns to understand emission behavior under practical operating conditions.

{% include section.html %}

## Research focus areas

{% for item in site.data.research %}
  {% include research.html item=item %}
{% endfor %}

{% include section.html %}