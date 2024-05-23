---
title: Home
author: Jim Lavrenz
date: May 23, 2024
---

## Projects

### [temp](https://jimlavrenz.github.io/) 

Testing 123

## Notes

<ul>
{% for item in site.notes %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
