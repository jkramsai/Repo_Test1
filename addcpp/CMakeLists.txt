cmake_minimum_required(VERSION 2.6)
project(addcpp)

add_executable(addcpp main.cpp)

install(TARGETS addcpp RUNTIME DESTINATION bin)
