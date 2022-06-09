---
title: Projects
layout: page
permalink: /projects/
---
<div class="project-list">
{% for project in site.projects %}
{% include project-list-item.html post=project %}
{% unless forloop.last %}
<hr/>
{% endunless %}
{% endfor %}
</div>