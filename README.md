# OpenGL

## Part A: Demo Screenshots 
### 1. TriangleColored.cpp 

A simple 2D colored triangle demonstrating basic OpenGL rendering. The triangle has three vertices with different colors (red, green, blue) that interpolate smoothly across the surface using the fragment shader.

<p align="center">
  <img src="SDL2_Version/res/tri.png" width="560">
</p>

g++ -std=c++11 TriangleColored.cpp glad/glad.c -o TriangleColored \
    -I./include -I/opt/homebrew/include -L/opt/homebrew/lib \
    -lSDL2 -framework OpenGL

### 2. Cube3D.cpp
A rotating 3D cube with different colored faces demonstrating 3D transformations. 

<p align="center">
  <img src="SDL2_Version/res/cube3D.gif" width="560">
</p>

g++ -std=c++11 -Wno-deprecated Cube3D.cpp glad/glad.c -o Cube3D \
    -I./include -I/opt/homebrew/include -L/opt/homebrew/lib \
    -lSDL2 -framework OpenGL

