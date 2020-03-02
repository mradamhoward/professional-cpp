cmake_minimum_required(VERSION 3.5)

project(c29_03_LoggerAdaptor LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)

add_executable(TestLoggerAdaptor TestLoggerAdaptor.cpp LoggerAdaptor.cpp)

