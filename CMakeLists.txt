cmake_minimum_required(VERSION 3.8)
project("cppjson")
set(CMAKE_CXX_STANDARD 17)
include_directories(${PROJECT_SOURCE_DIR}/lang)
add_executable(${PROJECT_NAME} example.cpp)

