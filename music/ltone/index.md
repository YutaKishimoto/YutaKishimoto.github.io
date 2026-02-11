---
layout: single
title: "L-tone"
permalink: /music/ltone/
---

# Albums
{% assign albums = site.albums | where: "project", "ltone" %}
{% for album in albums %}
- [{{ album.title }}]({{ album.url }})
{% endfor %}

# All Songs
{% assign songs = site.songs | where: "project", "ltone" %}
{% for song in songs %}
- [{{ song.title }}]({{ song.url }})
{% endfor %}
