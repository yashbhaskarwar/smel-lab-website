---
title: Research
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

SMEL is a sister laboratory of the Emissions and Fuels Research (EFR) Group at the College of Engineering, Center for Environmental Research and Technology (CE-CERT). The applications of my research extends from brake and tire wear particulate emissions from light-duty vehicles, heavy-duty trucks, and trains, vehicle and maritime emissions, air pollution impacts from battery fires, and emission mitigation strategies. 

{% include section.html %}

## Research focus areas

{% for item in site.data.research %}
  {% include research.html item=item %}
{% endfor %}

{% include section.html %}
