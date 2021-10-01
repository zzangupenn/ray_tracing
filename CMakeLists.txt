# CMakeList.txt : CMake project for ray_tracing, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("ray_tracing")

# Add source to this project's executable.
add_executable (ray_tracing "ray_tracing.cpp" "ray_tracing.h")

# TODO: Add tests and install targets if needed.
