cmake_minimum_required(VERSION 3.14)
project(MyApp) 

set(CMAKE_CXX_STANDARD 17)


file(GLOB_RECURSE SOURCE src/*.cpp)

add_executable(MyApp ${SOURCE})
target_include_directories(MyApp PRIVATE inc)