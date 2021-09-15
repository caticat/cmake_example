cmake_minimum_required(VERSION 2.8)
project(test1)

#message("psd:" ${PROJECT_SOURCE_DIR})
#message("bsdir:" ${BASE_DIR})

set(CMAKE_CXX_STANDARD 11)

add_executable(test1 main.cpp)

target_include_directories(test1 PRIVATE ${BASE_DIR}/helloworld)
target_link_libraries(test1 helloworld)

