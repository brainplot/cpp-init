cmake_minimum_required(VERSION 3.0)

if(POLICY CMP0092)
	cmake_policy(SET CMP0092 NEW)
endif()

project(my_awesome_project CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED true)
set(CMAKE_CXX_EXTENSIONS false)
set(CMAKE_EXPORT_COMPILE_COMMANDS true)

add_subdirectory(src)
