project('hello_World','cpp')
mylib_static = static_library('mylib_static','foo.cpp')
mylib_shared = shared_library('mylib_shared','foo.cpp')



dep = dependency('boost')
executable('helloWorld','main.cpp',link_with :mylib_static,dependencies:dep)