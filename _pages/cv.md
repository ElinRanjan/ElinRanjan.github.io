---
layout: archive
title: "CV"
description: "Curriculum vitae of Elin Ranjan Das: education, research experience, publications, presentations, teaching, and service."
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research interests
======
Quantum algorithms for scientific computing; quantum chemistry; hybrid oscillator–qubit architectures; Hamiltonian simulation; quantum differential equation solvers.

Education
======
* **Ph.D. in Electrical Engineering**, NC State University, Raleigh, NC. Aug 2024 – May 2029 (expected). GPA: 4.00/4.00
* **M.S. in Electrical Engineering**, NC State University, Raleigh, NC. Aug 2024 – Dec 2026 (expected). GPA: 4.00/4.00
* **B.Sc. in Electrical and Electronic Engineering**, Bangladesh University of Engineering and Technology (BUET), Dhaka, Bangladesh. Mar 2018 – May 2023. GPA: 3.86/4.00

Research experience
======
* **Ph.D. Research Intern**, NextGen Architecture Team, Future Computing Technologies Group, **Pacific Northwest National Laboratory**. Oct 2025 – present
  * Fall 2025 – Spring 2026 (part-time), Summer 2026 (full-time), Fall 2026 (part-time)
  * Developing algorithms for solving nonunitary dynamics on hybrid oscillator–qubit quantum systems.
  * Co-designing a simulation framework for nonlinear PDEs on superconducting-qubit hardware.
  * Investigating finite-resource implementations of hybrid quantum algorithms for scientific computing.
  * Running large-scale simulations on U.S. Department of Energy high-performance computing resources at the National Energy Research Scientific Computing Center (NERSC).
  * *Supervisors: Tim Stavenger, Muqing Zheng*

* **Graduate Research Assistant**, **[Quantum Engineering and Simulation Theory (QuEST) Lab](https://yuanliu.group/)** and **[Center for Hybrid Quantum Computing](https://cvdv.ncsu.edu/)**, Department of ECE, NC State University. Aug 2024 – present
  * Research quantum algorithms for simulating conical-intersection dynamics in coupled vibronic systems.
  * Develop a quantum ab initio multiple spawning framework for coupled electron–nuclear dynamics.
  * Investigate symmetry-adapted oscillator–qubit representations for molecular quantum simulation.
  * Collaborate with researchers at Oak Ridge National Laboratory on quantum algorithms for scientific computing.
  * *Advisor: Yuan Liu*

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

**In preparation**
* **Das, E. R.**, Albert, V. V., and Liu, Y. “Quantum theory of molecular phase space: symmetry-fixed rovibrational and nuclear-spin states.”
* **Das, E. R.**, Albert, V. V., and Liu, Y. “Symmetry-protected molecular qudit quantum computing.”
* **Das, E. R.**, Zheng, M., Stavenger, T., and Liu, Y. “Hardware-native programmable emulation in hybrid oscillator–qubit simulation of nonlinear dynamics.”

Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional service
======
* Reviewer: *Physical Review A*, *Physical Review Research*, *Physical Review Applied*, *APL Quantum*
* Reviewer: IEEE International Conference on Quantum Computing and Engineering (IEEE QCE)

Technical skills
======
* **Quantum computing software:** Qiskit (incl. Bosonic Qiskit), PennyLane (incl. hybridlane), QuTiP, D-Wave Ocean SDK, PsiQDK, Qumod

Professional memberships
======
* Student Member, IEEE
