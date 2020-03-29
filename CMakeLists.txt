cmake_minimum_required(VERSION 3.0)
project(my_awesome_project CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED true)
set(CMAKE_CXX_EXTENSIONS false)
set(CMAKE_EXPORT_COMPILE_COMMANDS true)

add_subdirectory(src)
