cmake_minimum_required(VERSION 3.1)

project(helloworld)

add_subdirectory("3rdParty/googletest")
add_subdirectory("test")

add_executable(${PROJECT_NAME} main.cc)
