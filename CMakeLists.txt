cmake_minimum_required(VERSION 3.12)
project(ELFIO CXX)

add_library(elfio INTERFACE)
target_include_directories(elfio SYSTEM INTERFACE "${PROJECT_SOURCE_DIR}/include")

add_subdirectory(examples)
