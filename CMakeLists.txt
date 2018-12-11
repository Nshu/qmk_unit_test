cmake_minimum_required(VERSION 3.5)
project(qmk_unit_test C)

set(CMAKE_C_STANDARD 99)

include_directories(que_module)
add_executable(qmk_unit_test main.c que_module/que_module.c)