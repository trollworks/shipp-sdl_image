cmake_minimum_required(VERSION 2.22)
project(SDL2_image)

set(BUILD_SHARED_LIBS OFF)
set(BUILD_STATIC_LIBS ON)

set(CMAKE_POLICY_DEFAULT_CMP0077 "NEW")

set(SDL2IMAGE_SAMPLES OFF)
set(SDL2IMAGE_VENDORED ON)
set(SDL2IMAGE_INSTALL ON)

add_subdirectory(upstream)
