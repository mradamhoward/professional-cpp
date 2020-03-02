cmake_minimum_required(VERSION 3.5)

project(c29_02_CarFactory LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)

add_executable(CarTest CarTest.cpp CarFactory.cpp)

