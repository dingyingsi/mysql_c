cmake_minimum_required(VERSION 3.16)
project(mysql_c C CXX)

set(CMAKE_C_STANDARD 11)

add_executable(mysql_c mysql/mysql_c.c)
add_executable(main main.c)