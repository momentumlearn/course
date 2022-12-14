---
title: Django REST Framework and Building APIs
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

## Intro to REST APIs

- [Notes: REST APIs 101](https://momentumlearn.notion.site/REST-API-Development-101-63eb6a74c0d34c3d8933919fd5e9de77)
- [RESTful APIs](https://restful-api-design.readthedocs.io/en/latest/intro.html) Read up through the "Standard Methods" subsection of the section on "Methods". You can read more if you want to but it gets pretty deep.
- [Safia Abdullah, You and Me Learn All About HTTP](https://dev.to/captainsafia/you-and-me-learn-all-about-http-with-safia-abdalla-3nd0)
- [Web APIs Explained By Selling Goods From Your Farm](https://blog.codeanalogies.com/2018/02/27/web-apis-explained-by-selling-goods-from-your-farm/)
- [What is a REST API?](https://www.youtube.com/watch?v=-mN3VyJuCjM)
- 📖 [A Beginner's Guide to REST](https://mlsdev.com/blog/81-a-beginner-s-tutorial-for-understanding-restful-api)
- [Notes: HTTP verbs/CRUD/SQL & REST URLs](https://docs.google.com/document/d/14nBPDt05rO7tFK3Pphq_CjjQhxLVmW3uNmncA7z88RY/edit?usp=sharing)

## REST API Design

- 📖 [REST APIs: How They Work and What You Need to Know](https://blog.hubspot.com/website/what-is-rest-api)
- [REST Resource Naming Guide](https://restfulapi.net/resource-naming/) This resource may be helpful in thinking about how to structure your urls.

## Django REST Framework Basics

- [Django REST Framework Documentation](https://www.django-rest-framework.org/)
- [Installation](https://www.django-rest-framework.org/#installation)
- [Django Chat: Django REST Framework](https://djangochat.com/episodes/django-rest-framework)
- [Django REST Framework: An Introduction - RealPython](https://realpython.com/django-rest-framework-quick-start/)

## Serializers

- [DRF Docs: Serializers](https://www.django-rest-framework.org/api-guide/serializers/)
- [DRF Docs: oModelSerializer](https://www.django-rest-framework.org/api-guide/serializers/#modelserializer)
- [DRF Docs: Serializer SlugRelatedField](https://www.django-rest-framework.org/api-guide/relations/#slugrelatedfield)
- [Using Different Read and Write Serializers in DRF](https://www.revsys.com/tidbits/using-different-read-and-write-serializers-django-rest-framework/)
- [How to Save Extra Data to a DRF Serializer](https://simpleisbetterthancomplex.com/tutorial/2019/04/07/how-to-save-extra-data-to-a-django-rest-framework-serializer.html) - _for example, when you need to associate a user with an object that you are creating._
- [Effectively using DRF Serializers](https://testdriven.io/blog/drf-serializers/)

## Views

### Class-based Views

- [Django docs: Introduction to class-based views](https://docs.djangoproject.com/en/4.1/topics/class-based-views/intro/) _This refers to class-based views in Django but it explains the concept, which you see applied in DRF._
- [Class-based vs. function-based views](https://simpleisbetterthancomplex.com/article/2017/03/21/class-based-views-vs-function-based-views.html) _This is about Django views in general, not specific to DRF._
- [DRF Docs: Class-based views](https://www.django-rest-framework.org/api-guide/views/) _This talks about `APIView`_.

### Generic Views

- [DjangoCon 2019: Generic View? What Is That and Why Would I Use It?, Felipe Lee](https://www.youtube.com/watch?v=qmKowZNmkCo) _Again about class-based views in Django but the explanation is relevant to what you will see in DRF._
- [Article on DRF Generic Views](https://testdriven.io/blog/drf-views-part-2/)

## DRF in more depth

- 💜 [Classy Django REST Framework](http://www.cdrf.co/) _This is **exceptionally** useful for working with classes in DRF_.
- [What You Should Know About DRF, Lacey Williams Henschel, PyCascades 2021](https://www.youtube.com/watch?v=06DJBu1zwoY)
- [What You Should Know About DRF, Part 1: ModelViewSet attributes and methods](https://www.laceyhenschel.com/blog/2021/2/22/what-you-should-know-about-drf-part-1-modelviewset-attributes-and-methods)
- [What You Should Know About DRF, Part 2: Customizing built-in methods](https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-drf-part-2-customizing-built-in-methods)
- [What You Should Know About DRF, Part 3: Adding custom endpoints](https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-django-rest-framework-part-3-adding-custom-endpoints)

## Permissions

- [DRF Docs: Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
- [DRF Permissions](https://testdriven.io/blog/drf-permissions/)
- [Built-in Permission Classes in DRF](https://testdriven.io/blog/built-in-permission-classes-drf/)
- [Custom Permissions in DRF](https://testdriven.io/blog/custom-permission-classes-drf/)
- [Pro Tip about DRF Permissions](https://www.revsys.com/tidbits/tip-about-drf-permissions/) _This shows how to combine permissions with logical operators like `and` and `or`_
