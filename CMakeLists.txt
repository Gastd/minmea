cmake_minimum_required(VERSION 3.1)
project(minnea)

add_definitions(-g -O3 -Wall)

set(SOURCES ../minmea.c)

add_library(minnea SHARED ${SOURCES})
