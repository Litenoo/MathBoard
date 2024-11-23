cmake_minimum_required(VERSION 3.10)
project(mathboard)

find_package(OpemCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(main mian.cpp)
target_link_libraries(main ${OpenCV_LIBS})