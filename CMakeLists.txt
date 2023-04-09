cmake_minimum_required(VERSION 3.20)
project(Prj_SquareWave C CXX ASM)

include(external/fetch_micro_tools.cmake)

add_executable(App_SquareWave main.c)

target_link_libraries(App_SquareWave microtoolslib_motor_dc)
