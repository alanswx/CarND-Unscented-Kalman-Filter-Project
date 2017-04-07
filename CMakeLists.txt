project(UnscentedKF)


cmake_minimum_required (VERSION 3.5)

add_definitions(-std=c++0x)
SET(CMAKE_CXX_FLAGS "-g3 -Wall -Wextra -Wno-unused -pg")

set(sources
   src/ukf.cpp
   src/main.cpp
   src/tools.cpp)

add_executable(UnscentedKF ${sources})
