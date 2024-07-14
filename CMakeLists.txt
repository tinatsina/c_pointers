cmake_minimum_required(VERSION 3.5)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_compile_options(-Wall -Wextra -std=c11)

project(SaNyati
  DESCRIPTION "attempt to learn C Pointers")

add_executable(app
  src/main.c)

