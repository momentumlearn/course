---
title: 'Models & Queries'
category: python
parent: References
layout: resource_list
---

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

### Models and Relationships

- [List of all Django Reference content related to Models](https://docs.djangoproject.com/en/4.1/ref/models/)
- [Don't forget! Django Best Practices: Custom User Model](https://learndjango.com/tutorials/django-custom-user-model)
- [Django Docs: Saving Model Instances](https://docs.djangoproject.com/en/4.1/ref/models/instances/#saving-objects)
- [Less Obvious Things to Do with the Django ORM](https://markusholtermann.eu/2019/03/less-obvious-things-to-do-with-djangos-orm/)
- [🍕 Tips for using Django's Many-to-Many Field](https://www.revsys.com/tidbits/tips-using-djangos-manytomanyfield/)
- [Django Related Objects Reference](https://docs.djangoproject.com/en/4.1/ref/models/relations/#related-objects-reference)

### Managers and QuerySets

- [Django Model Managers](https://docs.djangoproject.com/en/4.1/topics/db/managers)
- [Django Related Objects Reference](https://docs.djangoproject.com/en/4.1/ref/models/relations/#related-objects-reference)
- [Django QuerySets](https://docs.djangoproject.com/en/4.1/topics/db/queries/#retrieving-objects)

### Queries and Lookups

You can think of queries like questions you ask about your data, phrased in a way that the database can answer. Django has a built-in library (the Django ORM) that lets us do all the CRUD actions we need for our application, and more.

- [Django Queries: Retrieving Objects](https://docs.djangoproject.com/en/4.1/topics/db/queries/#retrieving-objects)
- [Django Queries: Field lookups](https://docs.djangoproject.com/en/4.1/topics/db/queries/#field-lookups)
- [Django Queries: Lookups that span relationships](https://docs.djangoproject.com/en/4.1/topics/db/queries/#lookups-that-span-relationships)
- [Django Queries: Lookups with Related objects](https://docs.djangoproject.com/en/4.1/topics/db/queries/#related-objects)
- [Pretty Printed Video: How Model Queries Work in Django](https://youtu.be/WimXjp0ryOo)
- [Pretty Printed Video: Querying One-to-Many Relationships in Django](https://youtu.be/iwNBwG8RBok )

### Django QuerySets and Managers

- [Django QuerySets](https://docs.djangoproject.com/en/4.1/topics/db/queries/#retrieving-objects)
- [Django Model Managers](https://docs.djangoproject.com/en/4.1/topics/db/managers)
- [Complex lookups with Q](https://docs.djangoproject.com/en/4.1/topics/db/queries/#complex-lookups-with-q-objects)
- [Database expressions with F objects](https://docs.djangoproject.com/en/4.1/ref/models/expressions/#django.db.models.F)

### Constraints

- [Django Docs: model constraints](https://docs.djangoproject.com/en/4.1/ref/models/options/#constraints) -> this gives you the general format/syntax
- [Django Docs: UniqueConstraint](https://docs.djangoproject.com/en/4.1/ref/models/constraints/#uniqueconstraint)

### Aggregate & Annotate

- [PrettyPrinted Video: Basics of Django Aggregations](https://youtu.be/2MFAV-arSuI)
- [Pretty Printed Video: How to Use Annotate in Django](https://youtu.be/KbwmdKl-QbI)
- [Django docs:Aggregate & Annotate](https://docs.djangoproject.com/en/4.1/topics/db/aggregation/)
- [Django docs: Combining Aggregations with other QuerySets](https://docs.djangoproject.com/en/4.1/topics/db/aggregation/#s-aggregations-and-other-queryset-clauses)
- [Aggregation Functions](https://docs.djangoproject.com/en/4.1/ref/models/querysets/#aggregation-functions) (e.g., `Avg`, `Count`, `Min`, `Max`)

### Using the shell (Django's interactive REPL, not pipenv shell and also not zsh)

- [Official Django docs on using the shell](https://docs.djangoproject.com/en/4.1/ref/django-admin/#shell)
- [How to use django-extensions `shell_plus`](https://django-extensions.readthedocs.io/en/latest/shell_plus.html#shell-plus)

### SQL

_Links in this section are really more information than you need right now, but it's relevant and interesting. Things included here are good to know but ok to save for later._

- [What is SQL?](https://www.techtarget.com/searchdatamanagement/definition/SQL)
- [SQL Basics: Learn X in Y minutes](https://learnxinyminutes.com/docs/sql/) -> this is a helpful reference for SQL syntax when you run into it. You do not need to write SQL for Django because the Django ORM does it for you, and it does it well. The Django docs often illustrate queries made by the ORM using SQL syntax, however, and you will find it helpful in your job to know the basics.
