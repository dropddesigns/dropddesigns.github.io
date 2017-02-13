---
layout: page
title: Services
permalink: /services/
---

<dl>
{% for service in site.data.services %}
  <dt><strong>{{ service.service }}</strong></dt>
  <dl>- {{ service.description }}</dl>
{% endfor %}
</dl>