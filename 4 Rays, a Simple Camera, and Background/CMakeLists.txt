#需求的最低cmake程序版本
cmake_minimum_required(VERSION 3.12)

#本工程的名字
project(RayTracer)

#本工程支持的C++版本
set(CMAKE_CXX_STANDARD 17)

#本工程主程序文件及输出程序名称
add_executable(rayTracer "main.cpp")