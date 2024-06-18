---
layout: archive
title: "CV/Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Computer Science, Yale University, 2024
* B.S. in Computer Science, Sichuan University, 2023
* B.S. in Fiancial Engineering, Sichuan University, 2023

ML & Research Experience
======
* Research Assistant, Yale University, Fall 2023 - Present
  * Advisor: Prof. Rex Ying
  * Research orientation: Graph Foundation Model, Graph Transformer, Information Bottleneck, Trustworthy Deep Learning

* Teaching Assistant, Yale University, Spring 2024
  * Instructor: Prof. Alex Wong
  * Course: CPSC 381/581, Introduction to Machine Learning
  * Topics: Stochastic Gradient Descent, Kernel Support Vector Machine, Principal Components Analysis, Neural Networks

* Machine Learning Engineer, Meituan, Summer 2023
  * Division: Mobike
  * Project: Graph nerual networks for bike station recommendations
    * Curation of large-scale graph dataset from spatio-temporal data
    * Implementation of GNNs; Model deployment and automation

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
