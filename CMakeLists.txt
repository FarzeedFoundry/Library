cmake_minimum_required(VERSION 3.9)

set (CMAKE_CXX_STANDARD 11)
set (CXX_STANDARD_REQUIRED)

project (TestLibrary)

add_library (TestLibrary STATIC TestLibrary.cpp)

configure_file( TestLibraryonfig.cmake.in TestLibraryConfig.cmake @ONLY )
