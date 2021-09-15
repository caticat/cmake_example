cmake_minimum_required(VERSION 2.8)
project(helloworld)

set(CMAKE_CXX_STANDARD 11)

add_library(helloworld SHARED helloworld.cpp)
