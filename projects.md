---
title: Projects
layout: page
permalink: /projects/
---
{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
{% endfor %}