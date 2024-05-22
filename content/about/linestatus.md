---
layout: layouts/base.njk
eleventyNavigation:
  key: LINE Status (2019)
  parent: Project
  order: 1
---

# LINE Status Series

## What is LINE Status Series?
LINE Status Series are writings that I made to accompany my LINE Status at the time, when LINE is still the rage, although it is dying.

## What is offLINE Series?
A series of writing I made that I didn't end up putting as a LINE Status, either because I forgot, or because I didn't think it fit the tone.

# LINE Status Series Archive

{% set postslist = collections['LINE Status'] %}
{% include "postslist.njk" %}

# offLINE Series Archive
{% set postslist = collections.offLINE %}
{% include "postslist.njk" %}
