cmake_minimum_required(VERSION 2.8.9)
project ("hello")


add_executable("${PROJECT_NAME}" "helloworld.cpp")
include(cTest)

add_test("test1" "${CMAKE_CURRENT_BINARY_DIR}/${PROJECT_NAME})