cmake_minimum_required(VERSION 3.20)
project(hello VERSION 1.0.0)

set(CMAKE_CXX_STANDARD 17)

add_executable(hello src/main.cpp src/hello.cpp)
target_include_directories(hello PUBLIC ${CMAKE_SOURCE_DIR}/include)