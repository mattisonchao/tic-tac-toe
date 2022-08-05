cmake_minimum_required(VERSION 3.23)
project(tic_tac_toe C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(tic_tac_toe tic_tac_toe.c)
