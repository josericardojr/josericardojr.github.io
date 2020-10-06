---
title: "Fluid Simulation"
excerpt: "Fluid simulation using the SPH (Smoothed Particle Hydrodynamics) method for my thesis master degree. For this project, I archived two way coupling between fluids and rigid bodies using a heterogeneous ambiente of CPU and GPU (CUDA) at the same time.<br/><img src='/images/500x300.png'>"
collection: portfolio
---
Fluid simulation using the SPH (Smoothed Particle Hydrodynamics) method for my thesis master degree. For this project, I archived two way coupling between fluids and rigid bodies using a heterogeneous ambiente of CPU and GPU (CUDA) at the same time.

Challenges

The main challenge of this project was distribute tasks among CPU and GPU and each of these processors have its own architecture.
Also, in order to minimize the data communication between GPU and CPU, which tends to reduce the overall speed, a new data structure was created.
Interaction between fluid and rigid body is done by covering the 3D model surface with a collection of spheres using a technique called Depth Peeling.
Features

CPU and GPU usage.
Two way interaction between fluids and rigid body.
Depth Peeling technique for discretizing rigid bodies.

