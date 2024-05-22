---
layout: layouts/base.njk
eleventyNavigation:
  key: Daily Project (2024)
  parent: Project
  order: 5
---

# Daily Project

## What is Daily Project?

Another attempt to write daily for the year of 2024, in the same vein as Two Thousand Twenty Words project, but without the strict rules. I'll be writing about whatever happened during that day, no matter if I didn't actually write it on the same day. It's an attempt for me to improve on my writing skills, and communicating what I feel through words. It shouldn't be something I forced myself to do.

# Daily Archive

{% set postslist = collections.Daily %}
{% include "postslist.njk" %}