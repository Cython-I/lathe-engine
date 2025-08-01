# Lathe Engine

**Lathe Engine** is a fast-paced, C++/OpenGL-powered 3D engine built from scratch, inspired by *Doom*,*Devil Daggers*, *Quake*, and the raw, high-speed brutality of classic arena shooters.

This project is part of a 12-week challenge to build a fully playable prototype FPS engine by **October 23, 2025**.

---

## Goals

- Fully custom FPS engine in C++17
- Modern OpenGL 3.3 core pipeline (no legacy OpenGL)
- Stylized arena combat inspired by Devil Daggers
- Particle system, enemy waves, scoring, and post-processing
- Single-executable build (no Unity, Unreal, or engines)

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
- [ ] Shooting system with raycasting
- [ ] Enemy spawner + basic AI
- [ ] Particle-based VFX (blood, trails, dust)
- [ ] Survival timer + scoring system
- [ ] Stylized effects (fog, screen shake, post-processing)
- [ ] 3D audio + ambient SFX
- [ ] Arena-based gameplay loop

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
