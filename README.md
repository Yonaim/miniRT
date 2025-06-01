# miniRT

A minimal ray tracing renderer written in C, implementing basic analytic rendering of 3D scenes. Developed from scratch as part of the 42Cursus.

## Description

miniRT is a small ray tracing program that renders simple 3D scenes using analytic geometry. The project focuses on implementing the core concepts of ray tracing, including intersections, lighting, and shading, without relying on external graphics libraries.

## Features

- Ray-sphere, ray-plane, and ray-cylinder intersections
- Phong reflection model (diffuse and specular shading)
- Point light source support
- Simple camera and viewport configuration
- BMP image export
- Minimal, dependency-free C implementation
- Command-line scene description file parsing

## Usage

```bash
make
./miniRT <scene_file.rt>
````

* The program expects a `.rt` file describing the scene.
* Example:

  ```bash
  ./miniRT scenes/example.rt
  ```

## Project Structure

```
Analytic-miniRT/
│
├── src/           # Source code files
├── include/       # Header files
├── scenes/        # Sample scene description files
├── Makefile
└── README.md
```

## Requirements

* C99 compiler (tested on gcc and clang)
* MiniLibX (for window and image display)

## Development Period

February 1, 2023 – March 15, 2023

## Authors

* [Yonaim](https://github.com/Yonaim)
* [hyeuu](https://github.com/hey-uu)
  
