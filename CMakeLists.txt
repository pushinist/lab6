cmake_minimum_required(VERSION 3.24)
set(CMAKE_CXX_COMPILER "/usr/bin/g++")
set(CMAKE_C_COMPILER "/usr/bin/gcc")
project(laba6)

set(CMAKE_CXX_STANDARD 23)

add_executable(laba6 main.cpp Func.hpp Func.cpp)
