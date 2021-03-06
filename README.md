# Mrag++ [![Build Status](https://travis-ci.org/AngeloG/MragPP.svg?branch=master)](https://travis-ci.org/AngeloG/MragPP)

Mrag++ is a C++ library for game development in SDL2. Its structure is loosely based on the concept of XNA (or Monogame).

It also supports Spine's Json format for animations.

Examples
========

You can find example projects in the `examples` folder.

Dependencies
============

The following dependencies are required for Mrag++ to build:

* [Cmake](http://www.cmake.org/)
* [SDL2.0](http://libsdl.org/download-2.0.php)
* [GLEW](http://glew.sourceforge.net/)
* libScratch (comes shipped)

Building
========

To build Mrag++, do the following:

    mkdir build
    cd build
    cmake ..

Or, for Windows (Visual Studio):

    mkdir visualstudio
    cd visualstudio
    cmake -G "Visual Studio 10 2010" ..

This will build a shared library to build against as `libMragpp.so`, `libMragpp.dylib` or `libMragpp.dll` - depending on your platform - inside of the `lib` folder in the project root.

License
=======

Mrag++ is licensed under the permissive [MIT license](LICENSE).
