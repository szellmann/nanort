# Simple GUI example with bullet3's OpenGLWindow + ImGui.

![](screenshot/nanort_gui.png)

## Coordinates

Right-handed coorinate, Y up, counter clock-wise normal definition.

## Requirements

* premake5
* OpenGL 2.x

## Build on Linux/MacOSX

    $ premake5 gmake
    $ make

## Build on MinGW(Experimental)

    $ premake5 gmake
    $ make

## Build on Windows

    > premake5 vs2013

Or 

    > premake5 vs2015

## Usage

Edit `config.json`, then

    $ ./bin/native/Release/view

### Mouse operation

* left mouse = rotate
* shift + left mouse = translate
* tab + left mouse = dolly(Z axis)

