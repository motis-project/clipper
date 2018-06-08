project(clipper)
cmake_minimum_required(VERSION 3.0)

include_directories(include)

file(GLOB_RECURSE clipper-files src/clipper.cpp)
add_library(clipper STATIC ${clipper-files})

