---
title: Phase 2 Back End
phase: 2
---

{% assign topics = site.data.phase2_topics | reverse %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.url %} [{{ topic.title }}]({% link {{topic.url}} %}){% else %} {{topic.title}} {% endif %}
: [Project]({{ topic.project_url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } [References]({% link {{ topic.references_url }} %}){: .label .references-label }
{% endfor %}
