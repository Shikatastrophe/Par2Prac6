---
layout: base.njk
title: Shika :)
---

# {{ title }}

- 21 y/o
- Working Hard
- Hardly Working
- Aspiring GameDev

[About Me!]({{ '/acerca' | url }})

## My top 3 top 3s

### Top 3 Albums

{% for album in collections.albums %}

- [{{album.data.title}}]({{ album.url | url }})

{% endfor %}

### Top 3 Animes

{% for anime in collections.animes %}

- [{{anime.data.title}}]({{ anime.url | url }})

{% endfor %}

### Top 3 Videogames

{% for vidya in collections.vidyas %}

- [{{vidya.data.title}}]({{ vidya.url | url }})

{% endfor %}