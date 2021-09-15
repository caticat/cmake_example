cmake_minimum_required(VERSION 2.8)
project(cpp_cmake_test)

message("base psd:" ${PROJECT_SOURCE_DIR})

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(helloworld)
add_subdirectory(test)

