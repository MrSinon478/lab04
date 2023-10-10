make_minimum_required(VERSION 3.27)

project(formatter_lib)

set(SOURCES
    formatter.cpp
    formatter.h
)

add_library(formatter STATIC ${SOURCES})