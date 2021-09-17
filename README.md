# Graphics Portfolio
List of graphics projects/experience

### Relevant Courses (UBC)
* CPSC 314 Computer Graphics
* MATH 221 Matrix Algebra
* MATH 264 Vector Calculus

### CPSC 314: Computer Graphics

Features
* Rendered with WebGL using ThreeJS + JavaScript

Environment mapping + shadow mapping

<img src="https://github.com/tristancalderbank/graphics-portfolio/blob/main/314_env_shadow.png" width="800">

Toon shading (quantized colors)

<img src="https://github.com/tristancalderbank/graphics-portfolio/blob/main/314_toon.png" width="800">

Ray tracer written in JavaScript in a couple hours

<img src="https://github.com/tristancalderbank/graphics-portfolio/blob/main/314_raytracer.png" width="800">

### Project: CPU Renderer in C++

CPU based rasterizing 3D renderer written in C++

https://github.com/tristancalderbank/TinyRenderer

Features
* Pure C++, no dependencies/graphics APIs
* Backface culling
* Z-buffering
* Perspective camera
* Lighting support for diffuse, normal, and specular textures
* Shadow mapping
* Screen-space ambient occlusion (SSAO)

Final render

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/shadow.png" width="800">

SSAO (inverted)

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/aocontrast.png" width="800">

Depth map seen by shadow camera

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/shadow_depth_buffer.png" width="800">

### Project: Real Time OpenGL renderer in C++

Rendering engine written in C++ using OpenGL 

https://github.com/tristancalderbank/TinyEngine

Features
* Supports loading glTF 2.0 models
* Skyboxes rendered with cubemaps
* [WIP] PBR-metallic workflow 
* Separate post-processing render step with tone-mapping/gamma correction
* Dear ImGui for debugging/tweaking parameters


<img src="https://github.com/tristancalderbank/graphics-portfolio/blob/main/engine_backpack.png" width="800">

