cmake_minimum_required(VERSION 3.28)

project(prog)

add_library(functions STATIC functions.c)

add_executable(main prog.c)

target_link_libraries(main functions)