# Graphics Portfolio
List of graphics projects/experience

### Relevant Courses (UBC)
* CPSC 314 Computer Graphics
* MATH 221 Matrix Algebra
* MATH 264 Vector Calculus

### Project: Real Time OpenGL PBR renderer in C++

Rendering engine written in C++ using OpenGL 

https://github.com/tristancalderbank/NanoEngine

<img src="https://github.com/tristancalderbank/NanoEngine/blob/master/screenshots/pbr_first_implementation.png">

Features
* PBR lighting with indirect image-based lighting (IBL)
* Cook-Torrance BRDF (based on Disney/Unreal 4 formulation)
* glTF 2.0 PBR model loading support
* Texture support: albedo, metallic, roughness, tangent-space normal, ao, emissive
* HDRI skyboxes
* Separate post-processing render step with tonemapping/gamma correction
* ImGui for debugging/tweaking parameters
* Free flight camera (WASD + mouse)

glTF 2.0 model loaded with PBR textures

<img src="https://github.com/tristancalderbank/graphics-portfolio/blob/main/engine_pbr.png" width="800">

### WebGL + JavaScript + ThreeJS

Features
* Environment mapping
* Shadow mapping
* Diffuse + bumpmap textures
* Phong lighting
* Skybox

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
* Rasterization using bounding boxes + barycentric coordinates
* Backface culling
* Z-buffering
* Perspective camera
* Phong lighting with support for diffuse, normal, and specular textures
* Shadow mapping
* Screen-space ambient occlusion (SSAO) using depth buffer + a raymarching algorithm

Final render

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/shadow.png" width="800">

SSAO (inverted)

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/aocontrast.png" width="800">

Depth map seen by shadow camera

<img src="https://github.com/tristancalderbank/TinyRenderer/blob/master/TinyRenderer/images/png/shadow_depth_buffer.png" width="800">
