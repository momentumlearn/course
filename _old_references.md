
{% assign learning_references = site.collections.references | where: 'category', 'learning' %}
{% assign dev_tools_references = site.references | where: 'category', 'dev tools' %}
{% assign front_end_references = site.references | where: 'category', 'front end' %}
{% assign js_references = site.references | where: 'category', 'js' %}
{% assign python_references = site.references | where: 'category', 'python' %}
{% assign orientation_references = site.references | where: 'category', 'orientation' %}

---

## Dev Tools

{: .reference-section-heading}

{% for reference in dev_tools_references %}
  {{reference}}
{% endfor %}

## HTML & CSS

{: .reference-section-heading}

{% for reference in front_end_references %}
  {{ reference }}
{% endfor %}

## JavaScript

{: .reference-section-heading}

{% for reference in js_references %}
  {{ reference }}
{% endfor %}

## Python

{: .reference-section-heading}

{% for reference in python_references %}
  {{ reference }}
{% endfor %}

## On Learning How To Code

{: .reference-section-heading}

{% for reference in learning_references %}
  {{ reference }}
{% endfor %}

## Getting Started at Momentum

{: .reference-section-heading}

{% for reference in orientation_references %}
  {{ reference }}
{% endfor %}
