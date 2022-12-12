---
layout: home
title: News
permalink: calendar
nav_order: 2
---

# News & Announcements

**Today's topics** are on the [list of topics by date]({% link calendar.md %}), along with links to **course material**, **references**, and **projects**.

## ✨ What's up today

{: .pt-3 .home-posts-headline }

{% assign daily_posts = site.daily_posts | reverse %}
{% for post in daily_posts %}
{{ post }}
{% endfor %}

## References

Here is where you can find curated information to support the projects you are working on.
