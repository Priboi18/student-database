# Ustawienie kompilatora C++
set(CMAKE_CXX_COMPILER "D:/programy/CodeBlocks/MinGW/bin/g++.exe")
# Ustawienie kompilatora C
set(CMAKE_C_COMPILER "D:/programy/CodeBlocks/MinGW/bin/gcc.exe")

cmake_minimum_required(VERSION 3.10)
project(student-database)
add_executable(${PROJECT_NAME} src/main.cpp)
