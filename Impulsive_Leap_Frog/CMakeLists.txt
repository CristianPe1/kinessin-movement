cmake_minimum_required(VERSION 3.10)

project("Impulsive_Leap_Frog")

add_executable(Impulsive_Leap_Frog main.cpp)

find_package(GSL REQUIRED)

target_link_libraries(Impulsive_Leap_Frog PRIVATE GSL::gsl)


