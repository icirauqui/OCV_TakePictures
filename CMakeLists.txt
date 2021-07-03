cmake_minimum_required(VERSION 2.4.6)

project(takepictures)

FIND_PACKAGE(OpenCV REQUIRED)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR})

add_executable(takepictures main.cpp)

target_link_libraries (${PROJECT_NAME}
${OpenCV_LIBS})

