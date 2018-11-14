cmake_minimum_required(VERSION 3.0)
project(CMakeExamples)

add_subdirectory(using_target_sources)

option(TARGET_SOURCES "Build with target_sources" ON)
message(STATUS "Build with target_sources: ${TARGET_SOURCES}")

option(TESTING "Include test targets" ON)
message(STATUS "Include test targets: ${TESTING}")

option(WINDOWS "Build for WINDOWS OS" OFF)
message(STATUS "Build for WINDOWS OS: ${WINDOWS}")
option(MAC "Build for MAC OS" OFF)
message(STATUS "Build for MAC OS: ${MAC}")
