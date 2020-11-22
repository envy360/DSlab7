cmake_minimum_required(VERSION 3.17)
project(DSlab7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(DSlab7
        AVLTree.cpp
        AVLTree.h
        main.cpp)
