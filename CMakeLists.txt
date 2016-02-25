cmake_minimum_required(VERSION 3.3)
project(CFuncMonitor)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Wcast-qual")

set(SOURCE_FILES main.cpp CFuncMonitor.h CFuncMonitor.cpp CFuncMonitor.cpp CFuncMonitor.h)
add_executable(CFuncMonitor ${SOURCE_FILES})