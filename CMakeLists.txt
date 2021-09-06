cmake_minimum_required(VERSION 3.0)
project(HelloWorld C)

set(CMAKE_C_STANDARD 11)

add_executable(HelloWorld main.c Calculator/calculator.c BMICalculator/BMICalculator.c)
