cmake_minimum_required(VERSION 3.14)
project(mpi1)

add_compile_options(-Wall -Wextra -Werror)
set(CMAKE_CXX_STANDARD 17)
add_executable(mpi1 main.cpp)
