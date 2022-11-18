cmake_minimum_required(VERSION 3.0 FATAL_ERROR)

project(matrix)

include(CMakeFuncs/functions.cmake)

add_subdirectory(tmat)
add_subdirectory(samples)
add_subdirectory(gtest)
add_subdirectory(test)
