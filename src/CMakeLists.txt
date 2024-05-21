cmake_minimum_required(VERSION 3.12)

add_executable(NoodleEngine main.cpp)

find_package(glfw3)
find_package(glad)
find_package(glm)
target_link_libraries(NoodleEngine PRIVATE glfw glad::glad glm::glm)