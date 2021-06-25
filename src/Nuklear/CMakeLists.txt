# CMakeList.txt : CMake project for Nuklear, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Nuklear")

# Add source to this project's executable.
add_library (Nuklear SHARED "Nuklear.cpp")

# TODO: Add tests and install targets if needed.
