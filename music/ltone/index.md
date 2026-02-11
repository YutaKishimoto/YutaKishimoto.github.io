---
layout: single
title: "L-tone"
permalink: /music/ltone/
---

# Albums
{% assign albums = site.albums | where: "project", "l-tone" %}
{% for album in albums %}
- [{{ album.title }}]({{ album.url }})
{% endfor %}

# All Songs
{% assign songs = site.songs | where: "project", "l-tone" %}
{% for song in songs %}
- [{{ song.title }}]({{ song.url }})
{% endfor %}
