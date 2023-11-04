cmake_minimum_required(VERSION 3.26)
project(thread_pool)

set(CMAKE_CXX_STANDARD 17)

add_executable(thread_pool main.cpp
        sly/task_queue.hpp
        sly/thread_pool.hpp)
