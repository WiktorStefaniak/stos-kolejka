cmake_minimum_required(VERSION 3.27)
project(stos_kolejka)

set(CMAKE_CXX_STANDARD 17)

add_executable(stos_kolejka main.cpp
        queue.h
        queue.cpp)
