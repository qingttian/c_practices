cmake_minimum_required(VERSION 3.8)
project(my_c)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES c_practices.c 1.cpp)
add_executable(c_practices ${SOURCE_FILES} 1.cpp)