cmake_minimum_required(VERSION 3.27.6)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_COMPILER g++)

project(QUANTFLOW
        VERSION 0.0.1
        DESCRIPTION
        "Algorithmic trading platform in C++"
        HOMEPAGE_URL https://github.com/scaevolabars/quantflow
        LANGUAGES C CXX
)

add_executable(${PROJECT_NAME} src/main.cpp)


