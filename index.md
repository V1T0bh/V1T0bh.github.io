---
title: Welcome! I'm Vito ✨
layout: my_home
---

## NUS Modules Taken:

{% assign modules = site.modules | where_exp: "item", "item.name == 'index.md'" | sort: "year" | sort: "semester" %}

{% assign grouped_modules = modules | group_by: "year" %}

{% for year_group in grouped_modules %}
### Year {{ year_group.name }}

  {% assign semester_groups = year_group.items | group_by: "semester" %}
  {% for semester_group in semester_groups %}
#### Semester {{ semester_group.name }}

  {% for module in semester_group.items %}
- [{{ module.title }}]({{ module.url | relative_url }})
  {% endfor %}
  {% endfor %}
{% endfor %}
