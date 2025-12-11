---
title: Team
nav:
  order: 3
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Lab Director & Principal Investigator

{% assign director = site.data.members | where: "role", "pi" %}
{% for person in director %}
{% include person.html person=person %}
{% endfor %}

{% include section.html %}

## Collaborating Research Faculty

{% assign collab_faculty = site.data.members | where: "role", "faculty" | where: "status", "current" %}
{% for person in collab_faculty %}
{% include person.html person=person %}
{% endfor %}

{% include section.html %}

## Students

{% assign students = site.data.members | where: "group", "students" | where: "status", "current" %}
{% for person in students %}
{% include person.html person=person %}
{% endfor %}

{% include section.html %}

## Alumni

{% assign alumni = site.data.members | where: "status", "alumni" %}
{% for person in alumni %}
{% include person.html person=person %}
{% endfor %}

{% include section.html %}