cmake_minimum_required(VERSION 3.20)
project(container_cpu_detection C)

set(CMAKE_C_STANDARD 11)

add_executable(container_cpu_detection
        detection.c
        sysconf_test.c)
