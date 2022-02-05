cmake_minimum_required(VERSION 3.20)
project(secondCourse C)

set(CMAKE_C_STANDARD 11)

add_executable(secondCourse main.c "labs 5b/lab5b.c")

add_subdirectory(libs)
target_link_libraries(second course data_structures)
target_link_libraries(second course algorithms)