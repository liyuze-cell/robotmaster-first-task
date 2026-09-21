cmake_minimum_required(VERSION 3.16)

project(hollow_robotmaster LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(hellow src/main.cpp)

target_compile_options(hellow PRIVATE -Wall -Wextra)