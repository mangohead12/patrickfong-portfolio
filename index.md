---
layout: splash
title: "Patrick Fong"
subtitle: "Mechanical Engineer • Robotics • Prototyping"
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
intro:
  - excerpt: "Welcome to my portfolio — a collection of projects in robotics, mechanical design, and prototyping."
---

[View Projects]({{ '/projects/' | relative_url }})



{% include archive.html
   title="Projects"
   collection=site.projects
   sort_by="date"
   sort_order="reverse"
   type="grid" %}
