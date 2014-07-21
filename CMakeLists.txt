cmake_minimum_required(VERSION 2.8)

project(jsoncpp)

include_directories(${PROJECT_SOURCE_DIR})

add_library(jsoncpp STATIC
  jsoncpp.cpp
)
