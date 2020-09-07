## 2 Getting started

Demo Compiling Manually

We take the same file from 1.2, and compile directly with the c++ compiler:

$ c++ -c -o hello.o hello.cpp

(make object file)


$ c++ -o hello hello.o

(make executable from object file)


$ c++ -o hello hello.cpp

(but you can skip the object step and just go directly to the executable)
