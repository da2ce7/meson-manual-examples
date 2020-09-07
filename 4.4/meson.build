project('library demo', 'cpp')

greeter_lib = static_library('greeter', 'greeter.cpp')

executable('hello', 'hello.cpp', link_with: greeter_lib)
