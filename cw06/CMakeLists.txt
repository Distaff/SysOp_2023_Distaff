﻿# CMakeList.txt : CMake project for PiotrKadziela-cw02
#
cmake_minimum_required (VERSION 3.8)

project ("cw06")

# Add source to this project's executable.
add_executable (cw06 "main.cpp" "server.h" "client.h" "common.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET cw06 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
