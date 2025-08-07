---
layout: default
title: Home
---

# Patrick Fong

Welcome to my project portfolio. I'm a mechanical engineer with a focus on robotics, mechanical design, and hands-on prototyping.

## Featured Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}