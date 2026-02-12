---
permalink: /test/
---

{% for item in site.mycollection %}
- item_ID: {{ item.item_id }}, Name:[{{ item.name }}]({{ item.url }}), URL:{{ item. url }}, ID: {{ item.id }}
{% endfor %}