cmake_minimum_required(VERSION 3.16)
project(compilers_101)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(source_dir "${PROJECT_SOURCE_DIR}/src")

file(GLOB source_files "${source_dir}/*.cpp")

add_executable(compilers_101
#        src/SumParser.cpp
#        src/HerediaCcodes/usuario.h
#        src/HerediaCcodes/main.c
#        src/HerediaCcodes/usuario.c
        src/main.c src/LinkedListParser.cpp)