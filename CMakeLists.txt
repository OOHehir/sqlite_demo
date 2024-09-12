cmake_minimum_required(VERSION 3.5.0)
project(sqlite_demo VERSION 0.1.0 LANGUAGES C)

add_executable(sqlite_demo main.c)
target_link_libraries(sqlite_demo sqlite3)

include(CTest)
enable_testing()
