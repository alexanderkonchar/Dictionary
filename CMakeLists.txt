cmake_minimum_required(VERSION 3.24)
project(Dictionary)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Dictionary
        Dictionary.h
        main.cpp)
