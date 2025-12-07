cmake_minimum_required(VERSION 4.1)
project(f-cpp-project)
include(3rdparty/f-lib/cmake/f.cmake)



add_subdirectory(3rdparty/f-lib)

add_subdirectory(modules/project)
