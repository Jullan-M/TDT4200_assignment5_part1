cmake_minimum_required(VERSION 3.14)
project(TDT4200_assignment5_part1 C)

set(CMAKE_C_STANDARD 11)

add_executable(main src/main.c src/mandelColours.h src/mandelCompute.h src/libs/bitmap.c src/libs/utilities.h)
