cmake_minimum_required(VERSION 3.13)
project(mines)

set(CMAKE_CXX_STANDARD 11)

add_executable(mines boids/src/app_boids.cpp)