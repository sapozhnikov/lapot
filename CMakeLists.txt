cmake_minimum_required(VERSION 3.25)
project(lapothpp LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)

enable_testing()

add_subdirectory(tests)
add_subdirectory(frontend)
