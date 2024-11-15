cmake_minimum_required(VERSION 3.5)
project(proj1)

add_library(proj1 STATIC ${PROJECT_SOURCE_DIR}/proj1.cpp)
target_include_directories(proj1 PUBLIC $<BUILD_INTERFACE:${PROJECT_SOURCE_DIR}>)
