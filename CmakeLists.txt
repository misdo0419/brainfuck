cmake_minimum_required(VERSION 3.16)
project(brainfuck)  # プロジェクト名

set(CMAKE_CXX_STANDARD 11)  # C++11 でのコンパイル

add_executable(brainfuck main.cpp)  # brainfuckという名前でビルド
