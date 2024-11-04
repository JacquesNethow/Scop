# SCOP: Basic GPU Rendering

Summary: This project is an introductory exploration of GPU rendering, where I’ll be using Metal and Swift to build a 3D rendering application on macOS. My goal is to deepen my understanding of Apple’s Metal framework and get hands-on experience with GPU rendering techniques through building an interactive application.

Core Features:

    - Render a 3D object in perspective view with rotation around its main axis, allowing control along the X, Y, and Z axes.
    - Toggle between color and texture modes with smooth transitions.
    - A demo with the 42 logo, rotating around its center axis, with optional custom textures (pony, kitten, or unicorn).

Technical Approach: I’ll be implementing this project in Swift, using Metal to take full advantage of the macOS GPU environment. I’ll use Metal Shading Language (MSL) to write custom shaders for transformations and rendering effects, with all core operations coded directly in Metal and minimal external dependencies.

Bonus Objectives:

    - Handle complex .obj models, including those with concave or non-planar surfaces.
    - Improve texture mapping to avoid stretching on object faces.
    - Experiment with simple lighting for enhanced 3D object display.

Project Goals: This project is an opportunity for me to explore GPU programming on macOS and learn more about Metal’s graphics capabilities, while building a functional 3D renderer from scratch.
