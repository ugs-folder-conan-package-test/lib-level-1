cmake_minimum_required(VERSION 3.19)
project(lib_level_1 CXX)
list(APPEND CMAKE_MODULE_PATH ${CMAKE_BINARY_DIR})
list(APPEND CMAKE_PREFIX_PATH ${CMAKE_BINARY_DIR})

set(CMAKE_CXX_STANDARD 20)

add_library(lib-1 INTERFACE)
target_include_directories(lib-1 INTERFACE cpp)
