cmake_minimum_required(VERSION 3.15)

project(SQLiteLib)

set(CMAKE_VERBOSE_MAKEFILE ON)

add_library(SQLite SHARED src/sqlite3.c)

target_include_directories(SQLite PRIVATE include/)