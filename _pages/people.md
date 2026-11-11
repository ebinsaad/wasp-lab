---
layout: page
title: People
permalink: /people/
description: Researchers, students, alumni, and collaborators of WASP Lab.
nav: true
nav_order: 5
---

<link rel="stylesheet" href="{{ '/assets/css/wasp-custom.css' | relative_url }}">

<p>
  WASP Lab brings together researchers, students, and collaborators
  working on reliable, dependable, and resilient computing,
  cybersecurity, trustworthy AI, and autonomous systems.
</p>

{% assign categories = "director,current,alumni,collaborator" | split: "," %}
{% for category in categories %}
{% assign members = site.people | where: "category", category | sort: "order" %}
{% if members.size > 0 %}
{% case category %}
{% when "director" %}{% assign section_title = "Lab Director" %}
{% when "current" %}{% assign section_title = "Current Members" %}
{% when "alumni" %}{% assign section_title = "Alumni" %}
{% when "collaborator" %}{% assign section_title = "Collaborators" %}
{% endcase %}

<h2 class="wasp-people-heading">{{ section_title }}</h2>
<div class="wasp-people-grid {% if category == 'director' %}wasp-director-grid{% endif %}">
{% for member in members %}
{% assign name_parts = member.name | split: " " %}
{% assign first_initial = name_parts.first | slice: 0 %}
{% assign last_initial = name_parts.last | slice: 0 %}
<div class="wasp-person-card {% if category == 'director' %}wasp-director-card{% endif %}">
{% if member.image %}
<img class="wasp-person-avatar" src="{{ member.image | relative_url }}" alt="{{ member.name | escape }}" loading="lazy">
{% else %}
<div class="wasp-person-avatar wasp-person-initials">{{ first_initial }}{{ last_initial }}</div>
{% endif %}
<div class="wasp-person-name">
{% if member.linkedin %}
<a href="{{ member.linkedin }}" target="_blank" rel="noopener noreferrer">{{ member.name }}</a>
{% else %}
{{ member.name }}
{% endif %}
</div>
<div class="wasp-person-role">{{ member.role }}</div>
{% if member.research %}
<div class="wasp-person-research">{{ member.research }}</div>
{% endif %}
{% if member.linkedin %}
<a class="wasp-person-link" href="{{ member.linkedin }}" target="_blank" rel="noopener noreferrer">LinkedIn</a>
{% endif %}
{% if member.website %}
<a class="wasp-person-link"
   href="{{ member.website }}"
   target="_blank"
   rel="noopener noreferrer">
  <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i>
  Faculty Profile
</a>
{% endif %}
</div>
{% endfor %}
</div>
{% endif %}
{% endfor %}