cmake_minimum_required(VERSION 3.14)
project(gameEngine)

set(CMAKE_CXX_STANDARD 17)

add_executable(gameEngine main.cpp GameEngine.h GameEngine.cpp)