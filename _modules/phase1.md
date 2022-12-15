---
title: Phase 1 Front End
phase: 1
---

{% assign topics = site.data.phase1_topics | reverse %}
{% assign projects =  site.data.projects %}

{% for topic in topics %}
{{ topic.date | date: "%B %-d" }}
: {% if topic.url %} [{{ topic.title }}]({% link {{topic.url}} %}){% else %} {{topic.title}} {% endif %}
: [Project]({{ projects[topic.project_name].url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .project-label } {% if topic.code_demo_url %} [Code Demo]({{ topic.code_demo_url }}){:target="_blank"}{:rel="noopener noreferrer"}{: .label .code-demo-label } {% endif %}
{% endfor %}
