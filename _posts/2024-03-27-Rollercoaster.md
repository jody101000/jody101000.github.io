---
title: OpenGL Roller Coaster Simulation
date: 2024-03-27 00:00:00 +0800
categories: [Projects]
tags: [OpenGL Core Profile, C++, GLSL, Linear Algebra, Spline Mathematics]     # TAG names should always be lowercase

description: Developed a real-time 3D roller coaster simulation using OpenGL core profile and GLSL shaders. 
image:
  path: /assets/img/rollercoaster.jpg
---
<!-- # OpenGL Roller Coaster Simulation -->

<!-- Developed a real-time 3D roller coaster simulation using OpenGL core profile and GLSL shaders.  -->
The project features a first-person camera view that allows users to experience realistic coaster rides along custom-designed tracks. 
By implementing Catmull-Rom splines and advanced graphics techniques, I created an immersive environment with physically accurate motion and high-performance rendering.

### Key Technical Achievements:
- Implemented custom GLSL shaders for per-pixel Phong lighting and texture mapping
- Designed and implemented a robust camera system using spline mathematics for smooth track following, including tangent vector calculation and orientation handling
- Built a high-performance rendering pipeline capable of maintaining 60+ FPS at 1280x720 resolution
<!-- - Created a modular track generation system using Catmull-Rom splines that supports both predefined and procedurally generated coaster layouts -->
- Integrated physics-based velocity calculations to simulate realistic gravitational effects on coaster movement
<!-- - Implemented a T-shaped double rail system with proper geometric construction and shading -->
- Created a skybox environment with dynamic texture mapping
<!-- - Developed a support structure generation system that automatically creates realistic track supports based on height and terrain -->
- Added real-time performance optimizations including recursive subdivision for spline rendering and efficient geometry batching

![img-description](/assets/img/rollercoaster.gif)
