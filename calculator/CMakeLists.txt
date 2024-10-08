cmake_minimum_required(VERSION 3.20)

project(calculator LANGUAGES CXX)

add_library(calculator SHARED
  calculator.cpp
  calculator.h)

add_executable(calc
  calculator.cpp
  calculator.h
  main.cpp)