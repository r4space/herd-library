cmake_minimum_required(VERSION 3.15)
project(herd_library)

set(CMAKE_CXX_STANDARD 17)

add_library(herd_library IBoard.cpp IBoard.h ICommandState.cpp ICommandState.h)