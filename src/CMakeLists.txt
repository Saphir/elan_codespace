cmake_minimum_required( VERSION 3.10 )

# Set the project name
project ( main_prj )

message( STATUS "CMAKE_PROJECT_NAME = ${CMAKE_PROJECT_NAME}" )
message( STATUS "PROJECT_SOURCE_DIR = ${PROJECT_SOURCE_DIR}" )

add_executable(main main.cpp)
