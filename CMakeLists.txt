cmake_minimum_required (VERSION 2.6)

project (test)

include_directories("${PROJECT_BINARY_DIR}")

add_executable(test test.c)
