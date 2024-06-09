cmake_minimum_required(VERSION 3.0.2)
project(nmpc_eigen)

add_compile_options(-std=c++17)

find_package(catkin REQUIRED COMPONENTS
  roscpp
  )

find_package(Eigen3 REQUIRED)

