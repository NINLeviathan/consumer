# consumer

## Purpose

This repo is part of a series of repos used to test a meson setup.  
This repo is to make use of files placed in the "src" folder in the [message](https://github.com/NINLeviathan/message) repo.  
~~This repo is supposed to use the meson.build file, supplied by the [messagebuild](https://github.com/NINLeviathan/messagebuild) repo, as build file for the [message](https://github.com/NINLeviathan/message) repo~~, Using subprojects/packagefiles for now.  

[Meson wrap dependency system manual](https://mesonbuild.com/Wrap-dependency-system-manual.html)

## Prerequisites

g++ compiler  
Meson build system

## Build with Meson

To build this project with the Meson build system, run the following commands on the command line.

```sh
meson setup builddir
```

```sh
cd builddir
```

```sh
meson compile
```
