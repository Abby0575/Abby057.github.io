---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, University of Minnesota Twin Cities, 2025

<!--
Work experience
======
* Summer 2025: Coming soon
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
-->

Skills
======
* Languages：
  * Python, Java, C/C++, C#, Kotlin, TypeScript, PHP, HTML, CSS, JavaScript, Bash/Shell, SQL
* Frameworks & Libraries：
  * React, Vue, Angular, Next.js, Node.js, Express.js, SpringBoot, Django, Flask, FastAPI, .NET
* Tools & Platforms：
  * Git, Jenkins (CI/CD), Docker, Kubernetes (K8s), Redis, Kafka, Elasticsearch, Unix/Linux
* Databases & Cloud: 
  * MongoDB, MySQL, PostgreSQL, AWS, Google Cloud Platform (GCP), Microsoft Azure

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{%- comment -%} 
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{%- endcomment -%}

{%- comment -%} 
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{%- endcomment -%}
  
Service and leadership
======
* AI researcher in CAMEL-AI.
* Software Engineer.
* Founder of Dingshi Co., Ltd.
