cmake_minimum_required(VERSION 2.8)

project(MyHTTPServer)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g -Wall -pthread")

set(CMAKE_BUILD_TYPE Debug)

add_executable(main main.cpp http_conn.cpp)