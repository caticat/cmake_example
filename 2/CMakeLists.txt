cmake_minimum_required(VERSION 2.8)
project(cpp_cmake_test)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(helloworld)

add_executable(cpp_cmake_test main.cpp)

target_link_libraries(cpp_cmake_test helloworld)

