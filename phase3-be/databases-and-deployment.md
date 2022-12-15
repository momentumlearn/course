---
layout: topic
title: Databases and Deployment
topic: Python
category: phase3-be
parent: Phase 3 Advanced Back End
nav_order: 1
published: true
---

## Objectives

- Using [PostgreSQL](https://www.postgresql.org/) with Django
- Deploying Django applications to [Render](https://www.render.com/)

## 🎯 Project: Habit Tracker

You'll be working on Habit Tracker this week.

[Habit Tracker GitHub Project Link]{{ page.project_url }}

It's important to read the project requirements **thoroughly** and to start to think about how you would do this project.

First steps: generate the project skeleton; make sure you are using Postgres; deploy to Render; and design your models. Make sure to create a diagram showing model fields and relationships. _Talk through with each other_ how you are thinking about this.

**By tomorrow**:

- Your application should be **deployed**.
- Your **models** should be functional -- that means you can see and work with them _at least_ in the admin (and ideally in the Django shell) and they do what they are supposed to do.
- You should be able to create habits and associated daily records in the Django shell (I recommend using [`shell_plus`](https://django-extensions.readthedocs.io/en/latest/shell_plus.html) which is available when you have `django-extensions` installed).

## 📖 Read | 📺 Watch | 🎧 Listen

_These are this week's required readings, videos, and/or podcasts. Read, watch, or listen, and **take notes**._

These are also listed under [Django references]({% link references/py-django.md %}).

### Deployment

- 📺 [Katie McLaughlin, What is Deployment, Anyway?](https://2021.djangocon.us/talks/what-is-deployment-anyway/)
- 📖 [Full Stack Python: Deployment](https://www.fullstackpython.com/deployment.html) - read through the section on Deployment Hosting Options, then read [Platform-as-a-service](https://www.fullstackpython.com/platform-as-a-service.html)
- 🎧 [Deploying and Running Django Web Apps in 2021](https://talkpython.fm/episodes/show/301/deploying-and-running-django-web-apps-in-2021)

### Databases & Data Modeling

- 📖 [Full Stack Python: Databases](https://www.fullstackpython.com/databases.html)
- 📖 [Full Stack Python: ORMs](https://www.fullstackpython.com/object-relational-mappers-orms.html)
- 📖 [What is a relational database?](https://www.techtarget.com/searchdatamanagement/definition/relational-database)
- 📺 [Entity Relationship Diagrams (ERD), from Lucid Chart](https://www.youtube.com/watch?v=QpdhBUYk7Kk)
- 📖 [Writing Safe Database Migrations in Django](https://markusholtermann.eu/2021/06/writing-safe-database-migrations-in-django/)
- 📺 [Database Design for Beginners](https://youtu.be/1VsSXRPEBo0) _This is a talk from RailsConf, which is focused on Ruby on Rails (Rails is a framework for building web applications in Ruby, very similiar to Django). The talk is an excellent introduction to how to think about your data model -- that is, the logic that drives the decisions you make about the models in your code and the structure of your database. Even though it uses Ruby examples you should be able to get the gist._

## 🔖 References

- [Deployment]({% link references/deployment.md %})
- [Databases]({% link references/databases.md %})
