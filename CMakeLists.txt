cmake_minimum_required (VERSION 2.6)
project (planner)
 
set(CMAKE_CXX_FLAGS "-std=c++14 -Wall -pedantic -O2")


# add the binary tree to the search path for include files
# so that we will find TutorialConfig.h
include_directories(include)
 
add_subdirectory(src)
add_subdirectory(examples)




