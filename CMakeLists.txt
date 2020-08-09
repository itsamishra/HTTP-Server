cmake_minimum_required(VERSION 3.16)

project(HTTP-Server)

add_compile_options(-Wall -g)

set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(
    ${PROJECT_NAME} 
	src/main.cpp
    )

set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 17)