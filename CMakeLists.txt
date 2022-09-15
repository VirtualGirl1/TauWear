cmake_minimum_required(VERSION 3.23)
project(TauWear)

set(CMAKE_CXX_STANDARD 23)

include_directories(lib)
add_executable(TauWear src/main.cpp)
