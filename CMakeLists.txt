cmake_minimum_required(VERSION 3.0.0)

add_definitions(-std=c++17)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")

set(CMAKE_BUILD_TYPE Debug)

project(Main VERSION 0.1.0)

add_executable(Main main.cpp)