cmake_minimum_required(VERSION 3.8)
project(my_c)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c c_practices.h snake.h)
add_executable(c_practices ${SOURCE_FILES} snake.c main.c c_practices.c)