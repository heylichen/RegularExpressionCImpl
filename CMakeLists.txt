cmake_minimum_required(VERSION 3.22)
project(RegularExpressionCImpl C)

set(CMAKE_C_STANDARD 17)

add_executable(RegularExpressionCImpl ThompsonNFA.c)
