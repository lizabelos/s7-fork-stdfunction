cmake_minimum_required(VERSION 3.0)
project(s7 VERSION 10.5 LANGUAGES C)

add_library(s7 INTERFACE)
target_sources(s7 INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/s7.cpp ${CMAKE_CURRENT_SOURCE_DIR}/s7.hpp)
target_include_directories(s7 INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})