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
* Ph.D in EE, GPA: 4.00/4.00, NC State University, May 2029 (expected)
* M.S. in EE, GPA: 4.00/4.00, NC State University, December 2026 (Expected)
* B.S. in EEE, GPA: 3.86/4.00, Bangladesh University of Engineering and Technology, 2023

Work experience
======
* Fall 2026: Intern (part-time), **Pacific Northwest National Lab**    
* Summer 2026: Intern (full-time), **Pacific Northwest National Lab**
  * Co-designing a simulation framework for nonlinear PDEs on superconducting-qubit hardware.
  * Running large-scale simulations on U.S. Department of Energy high-performance computing resources at the National Energy Research Scientific Computing Center (NERSC).
  * *Supervisor: Tim Stavenger, Muqing Zheng*

* Fall 2025 - Spring 2026: Intern (part-time), **Pacific Northwest National Lab**
  * Developing an algorithm framework for solving nonunitary dynamics on hybrid oscillator–qubit quantum systems.
  * Investigating finite-resource implementations of hybrid quantum algorithms for scientific computing.
  * *Supervisor: Tim Stavenger, Muqing Zheng*

* Fall 2024 - Present: Graduate Research Assistant, **[Quantum Engineering and Simulation Theory (QUEST) Lab](https://yuanliu.group/)**; **[Center for Hybrid Quantum Computing](https://cvdv.ncsu.edu/)**
  * Research quantum algorithms for simulating conical-intersection dynamics in coupled vibronic systems.
  * Develop a quantum ab initio multiple spawning framework for coupled electron-nuclear dynamics.
  * Investigate symmetry-adapted oscillator--qubit representations for molecular quantum simulation.
  * Collaborate with researchers at Oak Ridge National Lab on quantum algorithms for scientific computing. 
  * *Supervisor: Yuan Liu*
  
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


Reviewer
======
* Physical Review A
* Physical Review Research}
* IEEE International Conference on Quantum Computing and Engineering (IEEE QCE)
* APL Quantum
