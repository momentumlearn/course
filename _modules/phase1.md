---
title: Phase 1 Front End
phase: 1
---

{% assign topics = site.data.phase1_topics | reverse %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: [{{ topic.title }}]({% link {{topic.url}} %})
: [Project]({{ topic.project_url }}){: .label .project-label } [References]({% link {{ topic.references_url }} %}){: .label .references-label }
{% endfor %}
