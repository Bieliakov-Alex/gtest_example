cmake_minimum_required(VERSION 3.10.0)
project(ExampleGTestProject)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

enable_testing()

add_subdirectory(src)
add_subdirectory(test)
add_subdirectory(lib/googletest)
