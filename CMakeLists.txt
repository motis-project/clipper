project(clipper)
cmake_minimum_required(VERSION 3.0)

file(GLOB_RECURSE clipper-files src/clipper.cpp)
add_library(clipper STATIC ${clipper-files})
target_include_directories(clipper PUBLIC include)
