cmake_minimum_required(VERSION 2.8)
project(minnea)

add_definitions(-g -Wall -Wextra -Werror -std=c99 -D_DEFAULT_SOURCE -Dtimegm=mktime -D_POSIX_C_SOURCE=199309L -D_DEFAULT_SOURCE -D_DARWIN_C_SOURCE)

set(SOURCES ${CMAKE_SOURCE_DIR}/minmea.c)
add_library(minnea SHARED ${SOURCES})
