cmake_minimum_required(VERSION 3.14)
project(lodepng)

include_directories(.)
add_library(lodepng lodepng.cpp)
target_compile_definitions(lodepng PRIVATE -DLODEPNG_NO_COMPILE_ALLOCATORS)