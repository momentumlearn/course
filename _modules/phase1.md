---
title: Phase 1 Front End
phase: 1
---

{% assign topics = site.data.phase1_topics | reverse %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.url %} [{{ topic.title }}]({% link {{topic.url}} %}){% else %} {{topic.title}} {% endif %}
: [Project]({{ topic.project_url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } {% if topic.code_demo_url %} [Code Demo]({{ topic.code_demo_url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .code-demo-label } {% endif %}
{% endfor %}
