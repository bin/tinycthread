CMAKE_MINIMUM_REQUIRED(VERSION 3.14)

SET(CMAKE_C_STANDARD 11)

MESSAGE(STATUS "Building tinycthread library...")

ADD_LIBRARY(tinycthread STATIC
	src/tinycthread.c)
