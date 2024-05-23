---
title: Home
author: Jim Lavrenz
date: May 23, 2024
---

## Projects

### [ML Notebooks](https://jimlavrenz.github.io/notebooks) 

## Notes

<ul>
{% for item in site.notes %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
