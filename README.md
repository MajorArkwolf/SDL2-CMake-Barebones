<h1 align="center">
  <br>
  <img src="https://i.imgur.com/UQ4DFMq.png" alt="sdl2-logo" width="200"></a>
  <br>
    CMake SDL2 Example
  <br>
</h1>

<p align=center>
  <b> An example project to demonstrate using SDL2 in CMake, building from submodules. </b>
</p>

<p align="center">
  <a href="#usage">Usage</a> •
  <a href="#license">License</a>
</p>

## Usage
Clone the repository. Recurse the submodules.
```
git clone https://github.com/MajorArkwolf/SDL2-CMake-Barebones.git
git submodule update --init --recursive --depth 1
```

Configure, build, and run the project.
```
cmake -S . -B build && cmake --build build && ./build/sdl2-example
```

## License
This project is licensed under the ISC license. Please see the [`LICENSE.md`](LICENSE.md)
file for details.
