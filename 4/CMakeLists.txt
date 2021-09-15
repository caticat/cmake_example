cmake_minimum_required(VERSION 2.8)
project(cpp_cmake_test)

#message("base psd:" ${PROJECT_SOURCE_DIR})

set(CMAKE_CXX_STANDARD 11)

set(BASE_DIR ${PROJECT_SOURCE_DIR})

add_subdirectory(helloworld)
add_subdirectory(test)
add_subdirectory(test1)

