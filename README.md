# Lathe Engine

**Lathe Engine** is a fast-paced, C++/OpenGL-powered 3D engine built from scratch. The goal of this engine is to produce games that embody horror.
---

## Goals

- Fully custom Survival Horror engine in C++17
- Modern OpenGL

---

## Built With

- C++17
- [GLFW](https://www.glfw.org/) – window/input management
- [GLAD](https://glad.dav1d.de/) – OpenGL function loader
- [stb_image.h](https://github.com/nothings/stb) – image loading
- [Dear ImGui](https://github.com/ocornut/imgui) – debug UI
- CMake – build system

---

## Features

- [ ] OpenGL core renderer
- [ ] WASD + mouse look movement
- [ ] Game loop with delta time
- [ ] UI System for in game UI
- [ ] Enemy spawner + basic AI
- [ ] Particle-based VFX
- [ ] Stylized effects (fog, screen shake, post-processing)
- [ ] 3D audio + ambient SFX
- [ ] Atmospheric generation
- [ ] Level editor

---

## Build Instructions

### Requirements

- C++17 compiler (GCC / Clang / MSVC)
- CMake 3.10+
- Git

### Build (Linux / Mac / Windows)

```bash
git clone https://github.com/yourname/lathe-engine.git
cd lathe-engine
mkdir build && cd build
cmake ..
make
./LatheEngine
