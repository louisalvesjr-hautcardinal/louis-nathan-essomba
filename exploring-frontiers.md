---
title: "Exploring Frontiers (Research & Science)"
layout: page
permalink: /exploring-frontiers/
---

# Exploring Frontiers (Research & Science)

## Independent Studies
{% assign independent = site.research | where: "subsection", "independent_search" %}
{% for item in independent %}
- **{{ item.title }}**  
  [Read]({{ item.url }})
{% endfor %}

## Tech Company Threads
{% assign companies = site.research | where: "subsection", "tech-current-leader" %}
{% for item in companies %}
- **{{ item.title }}**  
  [Read]({{ item.url }})
{% endfor %}
