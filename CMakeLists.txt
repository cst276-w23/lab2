cmake_minimum_required(VERSION 3.14)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(Lab2)

add_executable(
 Lab2
 src/lab2.cpp
)

find_package(SFML 2.5.1 COMPONENTS graphics system window audio)

target_link_libraries(Lab2 sfml-graphics)
