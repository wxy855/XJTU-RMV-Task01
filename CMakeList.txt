# 指定CMake的最低版本要求
cmake_minimum_required(VERSION 3.10)

# 项目名称
project(HelloDXRMV)

# 设置C++标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 添加可执行文件，将1.cpp编译为名为hello的可执行程序
add_executable(hello 1.cpp)
