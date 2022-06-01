---
title: Events
layout: page
permalink: /events/
---
{% for event in site.events %}
### [{{ event.start }}: {{ event.title }}]({{ event.url }})
{% endfor %}