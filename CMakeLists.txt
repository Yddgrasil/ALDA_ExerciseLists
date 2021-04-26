cmake_minimum_required(VERSION 3.17)
project(ALDA_ExerciseLists C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(ALDA_ExerciseLists
        list.c
        list.h
        main.c)