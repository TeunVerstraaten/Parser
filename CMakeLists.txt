cmake_minimum_required(VERSION 3.23)
project(Parser)

set(CMAKE_CXX_STANDARD 17)

add_executable(Parser main.cpp src/Parser.cpp src/Parser.h src/Ast.cpp src/Ast.h)
