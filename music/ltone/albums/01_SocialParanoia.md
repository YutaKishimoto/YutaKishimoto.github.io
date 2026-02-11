---
layout: single
title: "SOCIAL PARANOIA"
project: "ltone"
album_id: "01"
release_year: 2018
cover: /assets/images/ltone/first-album.jpg
---

アルバムの説明を書く。

## Tracks
{% for song in site.songs %}
  {% if song.project == "ltone" and song.album_id == "01" %}
- [{{ song.title }}]({{ song.url }})
  {% endif %}
{% endfor %}
