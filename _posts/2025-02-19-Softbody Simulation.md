---
title: Softbody Simulation
date: 2025-02-19 00:00:00 +0800
categories: [Projects]
tags: [C++, OpenGL]     # TAG names should always be lowercase

image:
  path: /assets/img/jello.jpg
---

Developed a real-time physics simulation of a deformable jello cube using mass-spring systems and numerical integration methods. The project implements a physics engine that models elastic deformation, collision response, and external force fields. Built using C++ and OpenGL, this simulation demonstrates practical applications of physics-based animation and numerical methods.

{% 
  include embed/youtube.html 
  id='YvQonchWL2A' 
%}

### Key Technical Achievements:
- Implemented a mass-spring network system with 512 control points and three types of springs (structural, shear, bend) for realistic elastic behavior
<!-- - Built a robust physics engine using both Euler and 4th-order Runge-Kutta integration methods for accurate numerical simulation -->
- Developed efficient collision detection and response systems for interaction with a bounding box
- Created a non-homogeneous force field system with trilinear interpolation for complex environmental effects
- Optimized performance to maintain 100+ FPS at 640x480 resolution while handling complex physics calculations
- Implemented collision detection and response with additional geometric primitives (inclined plane, sphere)
