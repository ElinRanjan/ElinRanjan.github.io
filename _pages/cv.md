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
* Ph.D in ECE, NC State University, 2029 (expected)
* B.S. in EEE, Bangladesh University of Engineering and Technology, 2023

Work experience
======
* Summer 2026: Intern (full-time)
  * Pacific Northwest National Lab
  * Duties included: Developing novel quantum algorithms to solve nonlinear PDEs on hybrid continuous-variable/discrete-variable quantum architecture
  * Supervisor: Tim Stavenger, Muqing Zheng

* Fall 2025 - Spring 2026: Intern (part-time)
  * Pacific Northwest National Lab
  * Duties included: Developing novel quantum algorithms to simulate nonunitary dynamics on hybrid continuous-variable/discrete-variable quantum architecture
  * Supervisor: Tim Stavenger, Muqing Zheng

* Fall 2024 - Spring 2026: Graduate Research Assistant
  * Quantum Engineering and Simulation Theory (QUEST) Lab, NC State University
  * Duties included: Developing novel quantum algorithms to simulate molecular dynamics 
  * Supervisor: Yuan Liu
  
Skills
======
* Experienced in quantum computing packages
  * qiskit, bosonic qiskit
  * pennylane, hybridlane
  * qutip
  * dwave-ocean

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
