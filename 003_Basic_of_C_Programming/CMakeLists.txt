# Set the minimum reguired CMake version
cmake_minimum_required(VERSION 3.0)

# Set the project name
set (This Basic_of_C_Programming)

# Set the project type
project (${This} C CXX)

# Add executable
add_executable(${This} Sources/004_Print_Birth_Year.c)

# Include headers directory
target_include_directories(${This} PUBLIC Headers) 
