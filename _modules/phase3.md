---
title: Phase 3
phase: 2
---

{% assign topics = site.data.phase3_topics | reverse %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: **{{topic.tag}}**{: .label .{{topic.tag}}-label } {% if topic.url %} [{{ topic.title }}]({% link {{topic.url}} %}){% else %} {{topic.title}} {% endif %}
: [Project]({{ topic.project_url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } [References]({% link {{ topic.references_url }} %}){: .label .references-label }
{% endfor %}
