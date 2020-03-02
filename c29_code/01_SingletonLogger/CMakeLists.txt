cmake_minimum_required(VERSION 3.5)

project(c29_01_SingletonLogger LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)

add_executable(TestSingletonLogger TestSingletonLogger.cpp Logger.cpp)

