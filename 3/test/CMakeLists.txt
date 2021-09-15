cmake_minimum_required(VERSION 2.8)
project(test)

message("psd:" ${PROJECT_SOURCE_DIR})

set(CMAKE_CXX_STANDARD 11)

add_executable(test main.cpp)

target_link_libraries(test helloworld)

