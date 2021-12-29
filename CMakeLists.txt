cmake_minimum_required(VERSION 3.17)
project(liblt VERSION 1.0.0 LANGUAGES C CXX)
set(CMAKE_CXX_STANDARD 14)

option(LIBLT_BUILD_TESTS "Build Liblt's unit tests" ON)


add_library(liblt SHARED "")
target_sources(liblt
        PRIVATE
        src/P_00001_TwoSum.cpp
        )

