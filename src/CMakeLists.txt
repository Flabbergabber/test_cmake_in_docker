cmake_minimum_required(VERSION 3.7)
project(cmake_docker_test)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_CXX_COMPILER g++)

set(CMAKE_CXX_STANDARD 11)

add_executable(cmake_docker_test ${CMAKE_SOURCE_DIR}/test_cmake_in_docker.cpp)