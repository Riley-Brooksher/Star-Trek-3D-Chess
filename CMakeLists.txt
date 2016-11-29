cmake_minimum_required(VERSION 3.6)
project(Star_Trek_3D_Chess)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Star_Trek_3D_Chess ${SOURCE_FILES})