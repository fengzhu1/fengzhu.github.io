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
------
* M.S. in Computer Science and Technology, Soochow University(China), 2016
* Ph.D in Computer Science, Macquarie University(Australia), 2020

Work experience
------
* 2020 - Current: Algorithm Expert
  * Ant Group
  * Duties included: Search and recommender systems & LLM Agent

Publications
------
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
------
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
------
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
