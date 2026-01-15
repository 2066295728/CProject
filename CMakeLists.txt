cmake_minimum_required(VERSION 4.0)
project(CProject)

set(CMAKE_CXX_STANDARD 14)

include_directories(lua-5.4.8/src)

add_executable(CProject

        1_basic_demo.c
        2_printf_demo.c
        2_printf_plus.c
        2a_printf_demo.c)
