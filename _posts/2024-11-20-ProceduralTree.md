---
title: Procedural Tree Generation Using Space Colonization Algorithm
date: 2024-11-20 00:00:00 +0800
categories: [Projects]
tags: [OpenGL, C++, GLFW, GLSL]     # TAG names should always be lowercase

description: A real-time tree generation system implemented in C++ and OpenGL
image:
  path: /assets/img/procedural_tree.png
---

A real-time tree generation system implemented in C++ and OpenGL, based on the space colonization algorithm from Runions et al. (2007). The program simulates tree growth by modeling the competition for space between branches, producing biologically plausible tree structures. Users can interactively adjust growth parameters and visualize the results through a navigable 3D camera system.

### Key Technical Achievements:
- Real-time camera controls with GLFW (zoom, pan, rotate)
- Custom vertex and fragment shaders for realistic branch rendering
<!-- - Geometry instancing for efficient visualization of multiple trees -->
<!-- - Smooth branch thickness transitions using the pipe model -->
- Normal calculation for proper lighting and shading
- The system handles dynamic point removal and branch growth while maintaining interactive performance.
<!-- - GUI controls for growth parameters (influence radius, kill distance, growth distance) -->
<!-- - Multiple visualization modes showing growth progression and final structure -->
- Separated growth logic from rendering for better performance
- Efficient mesh generation using cylinder instancing
