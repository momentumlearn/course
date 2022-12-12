---
layout: home
title: Today
permalink: index.html
nav_order: 1
---

# Software Engineering Immersive

**Today's topics** are on the [calendar]({% link calendar.md %}), along with links to **course material**, **references**, and **lab assignments**.

## ✨ What's up today

{: .pt-3 .home-posts-headline }

{% assign daily_posts = site.daily_posts | reverse %}
{% for post in daily_posts %}
{{ post }}
{% endfor %}

## References

Here is where you can find curated information to support the projects you are working on.
