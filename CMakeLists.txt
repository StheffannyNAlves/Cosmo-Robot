
cmake_minimum_required(VERSION 3.16)

project(cosmo_linux LANGUAGES C)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

add_executable(cosmo_linux
    src/main.c
)

target_compile_options(cosmo_linux PRIVATE
    -Wall
    -Wextra
    -Wpedantic
)
