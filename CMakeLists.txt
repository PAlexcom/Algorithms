cmake_minimum_required(VERSION 3.2)
project(Algorithms)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES tests/tests.cpp )
add_executable(Algorithms ${SOURCE_FILES})