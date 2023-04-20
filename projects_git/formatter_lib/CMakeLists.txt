cmake_minimum_required(VERSION 3.10)

project(formatter_lib)

set(CMAKE_CXX_STANDARD 17)

add_library(formatter STATIC formatter.cpp formatter.h)
