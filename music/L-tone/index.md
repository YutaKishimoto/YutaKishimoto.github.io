---
layout: home
title: "L-tone"
permalink: /Music/L-tone/
---

# Albums
{% assign albums = site.albums | where: "project", "L-tone" %}
{% for album in albums %}
- [{{ album.title }}]({{ album.url }})
{% endfor %}

# All Songs
{% assign songs = site.songs | where: "project", "L-tone" %}
{% for song in songs %}
- [{{ song.title }}]({{ song.url }})
{% endfor %}
