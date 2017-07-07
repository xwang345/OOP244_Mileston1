cmake_minimum_required(VERSION 3.7)
project(OOP_Project)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        MS1/244_ms1_tester.cpp
        MS1/Date.cpp
        MS1/Date.h
        MS1/general.h)

add_executable(OOP_Project ${SOURCE_FILES})