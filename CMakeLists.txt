cmake_minimum_required(VERSION 3.23)
project(set_project)

set(CMAKE_CXX_STANDARD 17)

add_executable(set_project main.cpp Set.h Set.cpp BTree.cpp)
