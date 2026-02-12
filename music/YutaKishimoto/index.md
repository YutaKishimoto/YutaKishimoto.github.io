---
layout: single
title: "Yuta Kishimoto"
permalink: /Music/YutaKishimoto/
---

# Albums
{% assign albums = site.albums | where: "project", "YutaKishimoto" %}
{% for album in albums %}
- [{{ album.title }}]({{ album.url }})
{% endfor %}

# All Songs
{% assign songs = site.songs | where: "project", "YutaKishimoto" %}
{% for song in songs %}
- [{{ song.title }}]({{ song.url }})
{% endfor %}
