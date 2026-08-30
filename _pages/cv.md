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
* M.Sc. in Mechanics, Sichuan University, 2024-present
* B.Eng. in Civil Engineering, China University of Geosciences (Beijing), 2020-2024

Research Interests
======
* Tropical Cyclone Dynamics and Landfall Processes
* Surface–Atmosphere Interactions and Storm-Resolving Numerical Modelling
* Machine Learning for Atmospheric Science

Research Projects
======
* Reinforcement Learning for Pre-Landfall Tropical Cyclone Intensity Modification, Sichuan University    12/2025-present
  * Investigating typhoon intensity control by modifying sea surface temperature (SST) through numerical simulations.
  * Apply reinforcement learning to identify optimal control strategies.
  * Model SST changes through mixing colder deep water with warmer surface water.

* Landfalling tropical cyclones perturb Earth‘s rotation, Sichuan University    10/2024-present
  * Studied how landfalling tropical cyclones influence Earth’s rotation through angular momentum exchange.
  * Calculated frictional torque between cyclones and the land surface to reveal the underlying mechanism.
 
Research Experience
======
* Upcoming Research Intern, Fluid Mechanics Unit     10/2026-03/2027
Okinawa Institute of Science and Technology (OIST) · Okinawa, Japan
  
Skills
======
* Numerical simulation: CM1
* Data Analysis: ERA5; HURDAT2; NetCDF
* Programming: Python, MATLAB
* Machine Learning: Reinforcement Learning
* Scientific Computing: Linux; LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
