cmake_minimum_required(VERSION 3.8)
project(ProjetCPP)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Book.h Book.cpp Comic.h Poetry.h Comic.cpp Poetry.cpp Novel.h Novel.cpp Drama.h Drama.cpp Album.h Album.cpp Library.h Library.cpp Member.h Member.cpp)
add_executable(ProjetCPP ${SOURCE_FILES})