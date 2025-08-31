cmake_minimum_required(VERSION 3.20.0)
project(MyFirstGithub)

set(CMAKE_CXX_STANDARD 11)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)

include_directories(include)

aux_source_directory(${PROJECT_SOURCE_DIR}/src SRC_LIST)

add_executable(first_git ${SRC_LIST})
