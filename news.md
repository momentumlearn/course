---
layout: home
title: News
permalink: daily-update
nav_order: 2
---

## News & Announcements

_See also [**list of topics by date**]({% link calendar.md %})._


{: .pt-3 .home-posts-headline }

{% assign daily_posts = site.daily_posts | reverse %}
{% for post in daily_posts %}
{{ post }}
{% endfor %}
