cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
project(Labo1)

add_executable(Labo1 Labo1.c)
include_directories(/home/pi/Documents/Labo/Labo1)

target_link_libraries(Labo1 mariadb)