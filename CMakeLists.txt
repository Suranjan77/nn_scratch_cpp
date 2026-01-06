cmake_minimum_required(VERSION 3.10)

project(nn_scratch VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(nn_scratch src/main.cpp)

target_include_directories(nn_scratch ${CMAKE_SOURCE_DIR}/src)
