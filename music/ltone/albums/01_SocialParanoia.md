---
layout: single
title: "SOCIAL PARANOIA"
project: "ltone"
album_id: "01"
release_year: 2018
cover: /assets/images/l-tone/first-album.jpg
---

アルバムの説明を書く。

## Tracks
{% for song in site.songs %}
  {% if song.project == "l-tone" and song.album_id == "first-album" %}
- [{{ song.title }}]({{ song.url }})
  {% endif %}
{% endfor %}
