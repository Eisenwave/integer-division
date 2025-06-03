cmake_minimum_required(VERSION 3.5)
project(integer-division)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(test test.cpp intdiv.hpp)
