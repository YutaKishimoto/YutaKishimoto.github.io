---
layout: single
title: "SOCIAL PARANOIA"
project: "ltone"
album_id: "01"
release_year: 2011
cover: /assets/images/ltone/first-album.jpg
---

text

## Tracks
{% assign tracks = site.songs | where: "project", "ltone" | where: "album_id", "01" | sort: "track_number" %}
{% for song in tracks %}
- {{ song.track_number }}. [{{ song.title }}]({{ song.url }})
{% endfor %}
