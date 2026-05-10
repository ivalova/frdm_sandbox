cmake_minimum_required(VERSION 3.10)

# Project name and language
project(FRDM C)

# Use C11 standard
set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

# Collect source files
set(SOURCES
    src/main.c
)

# Create executable
add_executable(${PROJECT_NAME} ${SOURCES})
