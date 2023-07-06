cmake_minimum_required(VERSION 3.25)
project(cpp_basic)

set(CMAKE_CXX_STANDARD 17)

include_directories(cpp17)

add_executable(cpp_basic
#        cpp17/cpp17a.cpp
        stl/umap.cpp
        )
