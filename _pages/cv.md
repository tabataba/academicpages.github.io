---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My full Curriculum Vitae can be downloaded here: <u><a href="https://tabataba.github.io/files/CV_Fachreddin_Tabataba-Vakili_2018_Mar.pdf">pdf</a>.</u>

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

  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



