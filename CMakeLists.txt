cmake_minimum_required(VERSION 3.31)
project(RVCOSA C)

set(CMAKE_C_STANDARD 99)

add_executable(RVCOSA
        main.c
        src/RVUtility.c
        include/RVUtility.h)

target_include_directories(RVCOSA PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)
