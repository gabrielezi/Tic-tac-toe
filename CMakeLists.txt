cmake_minimum_required(VERSION 3.13)
project(myServer C)

set(CMAKE_C_STANDARD 99)
link_libraries(ws2_32 wsock32)

add_executable(myServer src/server.c)