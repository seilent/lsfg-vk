cmake_minimum_required(VERSION 3.10)
project(lsfg-vk LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_POSITION_INDEPENDENT_CODE ON)

add_subdirectory(lsfg-vk-common)
add_subdirectory(lsfg-vk-backend)
add_subdirectory(lsfg-vk-layer)
