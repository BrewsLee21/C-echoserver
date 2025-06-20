cmake_minimum_required(VERSION 3.31)
project(echoserver C)

set(CMAKE_C_STANDARD 17)

add_executable(echoserver server.c)
