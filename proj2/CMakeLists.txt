cmake_minimum_required(VERSION 3.23)

project(proj2 LANGUAGES CXX)
add_library(proj2 STATIC)
target_link_libraries(proj2 INTERFACE proj1)
target_sources(proj2 PRIVATE proj2.cpp)
