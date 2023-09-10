# Minimum required version of CMake
cmake_minimum_required(VERSION 3.0)

# Project name and description
project(numbersGoingUppp CXX)

# Add source files
add_executable(numbersGoingUppp src/main.cpp)

# Set C++ standard (optional)
target_compile_features(numbersGoingUppp PRIVATE cxx_std_11)

target_include_directories(numbersGoingUppp PRIVATE include/)