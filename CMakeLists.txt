cmake_minimum_required(VERSION 3.0.0)
project(markdown2html VERSION 1.2.2)

add_compile_options(-Wall -Wextra -Wpedantic -std=c++1z)

add_executable(markdown2html main.cpp stringProcess.cpp Settings.cpp MarkdownSource.cpp)
