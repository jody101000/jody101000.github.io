---
title: Ray Tracing
date: 2024-04-19 00:00:00 +0800
categories: [Projects]
tags: [Ray Tracing, C++]     # TAG names should always be lowercase

description: Designed and implemented ray tracing algorithms to accurately trace rays through complex scenes involving triangles and spheres. 
image:
  path: /assets/img/spheres_blcack.jpg
---

- Recursive reflection.
- Soft shadow. Sublights are in a sphere centered at the light position with a given radius.
- Anti aliasing. Each pixel color is determined by a 3 x 3 pixel block centered at itself. If it is on the edge, missing pixels in the block will be replaced by itself. Pixel colors in the 3 x 3 block are weighted for calculating the average.
- Parallel computing using OpenMP. Parallel for each pixels.

![img-description](/assets/img/box_black.jpg)
![img-description](/assets/img/table_black.jpg)
![img-description](/assets/img/toy_black.jpg)
