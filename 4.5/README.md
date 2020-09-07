## 4 Building blocks of a software project

In this simple project we demostrate the simplicity of Meson.

The Hello Main File:
* hello.cpp

Calls the Greeter Libary (in it's own subfolder):
* greeter/greeter.h
* greeter/greeter.cpp

Specifed by it's own meson.build file:
* greeter/meson.build

Using an updated Meson Build File:
* meson.build

To build:

$ meson build
$ ninja -C build

Run sample project:

$ build/hello


