## 4 Building blocks of a software project

In this simple project we demostrate the simplicity of Meson.

The Hello Main File:
* hello.cpp

Calls the Greeter Libary:
* greeter.h
* greeter.cpp

Using an updated Meson Build File:
* meson.build

To build:

$ meson build
$ ninja -C build

Run sample project:

$ build/hello


