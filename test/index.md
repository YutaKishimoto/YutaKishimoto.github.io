---
permalink: /test/
---

{% for item in site.collectionTest %}
- ID: {{ item.id }}, Name:{{ item.name }}
{% endfor %}