# SCOP: Basic GPU Rendering

Summary: This project is an introductory exploration of GPU rendering, i will be using both MoltenVK (a Vulkan implementation for macOS) and C++. The goal is to create a 3D rendering application that loads and displays a .obj model in perspective view. The rendered object will rotate around its main axis, be controllable along three spatial axes, and support smooth transitions between colored and textured modes.

Core Features:

    - Render a 3D object with rotation and perspective effects, allowing dynamic control along X, Y, and Z axes.
    - Toggle between a colored and textured view of the model with smooth transitions.
    - Demonstration of a rotating 42 logo with optional custom textures (pony, kitten, or unicorn).

Technical Approach: Implemented in C++ and using Vulkan through MoltenVK to provide macOS compatibility. A classic Makefile is used for building, and only minimal external libraries are used for window and event management. All 3D object loading, matrix transformations, and shader handling are coded directly, adhering to project constraints.

Bonus Objectives:

    - Support for complex .obj models with non-planar or concave surfaces.
    - Refined texture application to avoid stretching artifacts on object faces.
