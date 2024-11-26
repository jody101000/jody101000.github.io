---
title: Ray Tracer
date: 2024-04-19 00:00:00 +0800
categories: [Projects]
tags: [Ray Tracing, C++, Linear Algebra]     # TAG names should always be lowercase

description: Developed a custom ray tracer from scratch in C++
image:
  path: /assets/img/spheres_blcack.jpg
---

Developed a custom ray tracer from scratch in C++ that generates photorealistic images by simulating light behavior. The renderer supports various optical phenomena including shadows, reflections, and soft lighting effects, while maintaining efficient performance through optimized ray intersection algorithms and spatial partitioning.

![img-description](/assets/img/box_black.jpg)

### Key Technical Achievements:
- Implemented a complete ray tracing pipeline with support for multiple geometric primitives (spheres, triangles) and Phong shading
- Developed efficient ray-object intersection algorithms using analytical and geometric solutions
- Created a physically-based lighting system with multiple light sources, shadows, and global illumination
- Built an interpolation system for smooth shading using barycentric coordinates for mesh geometry
- Optimized rendering performance through spatial partitioning and early ray termination techniques

- Implemented recursive ray tracing for realistic reflections with configurable depth
<!-- - Added Monte Carlo sampling for soft shadows and improved antialiasing -->
<!-- - Created motion blur effects for moving objects using temporal sampling -->
<!-- - Developed a flexible scene description parser supporting complex 3D scenes -->
- Achieved antialiasing through adaptive supersampling
- Implemented multi-threaded rendering using OpenMP, achieving near-linear speedup by parallelizing pixel computations across available CPU cores

![img-description](/assets/img/table_black.jpg)
![img-description](/assets/img/toy_black.jpg)
