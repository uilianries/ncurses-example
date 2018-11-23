cmake_minimum_required(VERSION 2.8.11)
project(ncurses-example C)

add_executable(${PROJECT_NAME} ${CMAKE_CURRENT_SOURCE_DIR}/main.c)
target_link_libraries(${PROJECT_NAME} ncurses)