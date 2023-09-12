# ---------------------------------------------------
# Root Cmake file for learning cpp


# ---------------------------------------------------

# minimum CMake version
cmake_minimum_required(VERSION 3.20)

# project level information such as the name, language or version number
project(Learn_Cpp)

SET(MAIN_SOURCE main.cpp)
add_executable(Learn_CPP ${MAIN_SOURCE})
