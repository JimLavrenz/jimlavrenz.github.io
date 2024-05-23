---
title: Home
author: Jim Lavrenz
date: May 23, 2024
---

## Projects

### [temp](https://jimlavrenz.github.io/notebooks) 

Testing 123 $x^2$

## Notes

<ul>
{% for item in site.notes %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
