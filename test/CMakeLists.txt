cmake_minimum_required(VERSION 3.1)

include_directories("${gtest_SOURCE_DIR}/include")

add_executable(unittest test.cc)
target_link_libraries(unittest gtest gtest_main)
