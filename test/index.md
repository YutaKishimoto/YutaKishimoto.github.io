---
permalink: /test/
---

{% for item in collectionTest %}
- ID: {{ item.id }}, Name:{{ item.name }}
{% endfor %}