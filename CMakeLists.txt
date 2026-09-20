# 指定 CMake 的最低版本
cmake_minimum_required(VERSION 3.10)

# 给项目起个名字
project(MyFirstProject)

# 告诉编译器：把 main.cpp 编译成一个叫 main 的程序
add_executable(main main.cpp)