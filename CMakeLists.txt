cmake_minimum_required(VERSION 3.12)
project(ci_testing C)

set(CMAKE_C_STANDARD 99)

add_executable(ci_testing main.c version.h)