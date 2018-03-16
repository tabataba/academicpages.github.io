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
* B.Sc. in Physics, Technische Universität Berlin, 2011
* M.Sc. in Physics, Technische Universität Berlin, 2013
* DPhil in Atmospheric Oceanic and Planetary Physics, University of Oxford, 2017

Research experience
======

* 2017- : Postdoctoral Research Scholar
  * NASA Jet Propulsion Laboratory, California Institute of Technology
  * Duties included: Characterizing and understanding polar cyclones on Jupiter, Coordinating Earth-based observation efforts of Jupiter
  * Supervisor: Glenn S. Orton


* 2011-2013: Student Research Assistant
  * Leibniz Institute for Astrophysics Potsdam (AIP) 
  * Duties included: software development for integral field spectrometer data reduction tool p3d
  * Supervisor: Christer Sandin

  {% for post in site.research %}
    {% include archive-single.html %}
  {% endfor %}

  
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
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



