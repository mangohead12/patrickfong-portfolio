---
layout: splash
title: "Patrick Fong"
subtitle: "Mechanical Engineer • Robotics • Prototyping"
header:
  overlay_color: "#000"
  overlay_filter: "0.3"

<img src="{{ '/assets/images/headshot.jpg' | relative_url }}" alt="Patrick Fong" style="width:180px; border-radius:50%; margin-bottom:15px;">

Hi, I’m Patrick — a mechanical engineer specializing in robotics, mechatronics, and rapid prototyping.  
I design and build systems from concept to hardware, focusing on practical, manufacturable solutions.


[View Projects]({{ '/projects/' | relative_url }})



{% include archive.html
   title="Projects"
   collection=site.projects
   sort_by="date"
   sort_order="reverse"
   type="grid" %}
