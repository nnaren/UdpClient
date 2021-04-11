cmake_minimum_required(VERSION 3.8)
Set(This Example)
project(${This} CXX)

Set(Sources
    Client.cpp
)

add_executable(${This} ${Sources})