---
permalink: /test/
---

{% for item in site.mycollection %}
- ID: {{ item.id }}, Name:{{ item.name }}
{% endfor %}