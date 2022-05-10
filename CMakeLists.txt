cmake_minimum_required(VERSION 3.4)
project(libdivide CXX)

add_library(libdivide INTERFACE)

target_include_directories(libdivide INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
