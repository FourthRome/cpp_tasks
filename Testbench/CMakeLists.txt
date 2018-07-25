cmake_minimum_required(VERSION 3.10)
project(Testbench)



set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17 -lm -O2 -Wall")

add_executable(Testbench main.cpp)

