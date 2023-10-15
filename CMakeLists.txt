cmake_minimum_required(VERSION 3.27.6)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_COMPILER g++)

project(QUANTFLOW)

target_link_libraries(QUANTFLOW )



add_executable(${PROJECT_NAME} main.cpp)


