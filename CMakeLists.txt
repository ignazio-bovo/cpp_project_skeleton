cmake_minimum_required(VERSION 3.14)
project(<project>)

add_subdirectory(src)
set(CMAKE_CXX_STANDARD 17)

add_executable(<test_out> testmain.cpp)
