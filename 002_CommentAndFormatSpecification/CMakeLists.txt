# Set the minimum required CMake version
cmake_minimum_required(VERSION 3.0)

# Set the project name
set(This CommentAndFormatSpecification)

# Set the project type
project(${This} C CXX)

# Add executable
add_executable(${This} Sources/004_CommentAndFormatSpecification.c)

# Include headers directory
# target_include_directories(${This} PUBLIC Headers)
