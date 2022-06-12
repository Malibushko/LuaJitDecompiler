cmake_minimum_required(VERSION 3.13) 
project(LuaJitDecompiler)               
set(CMAKE_CXX_STANDARD 20)            

set(SOURCE_FILES main.cpp)

add_executable(LuaJitDecompiler ${SOURCE_FILES})