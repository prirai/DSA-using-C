cmake_minimum_required(VERSION 3.0)

project(dsa LANGUAGES C)

add_executable(dsa main.c)

install(TARGETS dsa RUNTIME DESTINATION bin)
