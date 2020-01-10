cmake_minimum_required(VERSION 3.3)
project(Lsn14_Example_semaphore)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Werror")

set(SOURCE_FILES main.c)
add_executable(semaphore ${SOURCE_FILES})
target_link_libraries(semaphore pthread)
