---
title: Phase 2 Back End
phase: 2
---

{% assign topics = site.data.phase2_topics | reverse %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: [{{ topic.title }}]({% link {{topic.url}} %})
: [Project]({{ topic.project_url }}){: .label .project-label } [References]({% link {{ topic.references_url }} %}){: .label .references-label }
{% endfor %}
