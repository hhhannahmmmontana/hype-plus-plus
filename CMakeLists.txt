cmake_minimum_required(VERSION 3.26)
project(hype++)

set(CMAKE_CXX_STANDARD 14)

include_directories(lib)

add_executable(hype++
        main.cpp
        lib/хайп++.h)
