cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Labo1)

add_executable(Labo1 Labo1.c)
include_directories(/usr/include/mariadb /usr/include/mariadb/mysql)

target_link_libraries(Labo1 mariadb)