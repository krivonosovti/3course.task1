cmake_minimum_required(VERSION 3.27)
project(3course.task_1)

set(CMAKE_CXX_STANDARD 17)

add_executable(3course task_1/task_1.cpp
        task_1/implementation.cpp
        basic_function.cpp
        basic_function.h
        task_2/root_search.cpp
        task_2/task_2_main.cpp
        main.cpp
        task_2/root_search.h
        task_3/task_3_main.cpp
        task_3/task_3_main.h
        task_2/reverse_interpolation.cpp
        task_2/reverse_interpolation.h
)
