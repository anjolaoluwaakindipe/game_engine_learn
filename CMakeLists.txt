cmake_minimum_required(VERSION 3.20.0)
project(game_engine_learn VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_FLAG "-Wall -Wextra")

include(CTest)
enable_testing()

find_package(wxWidgets CONFIG REQUIRED)
add_subdirectory(src)


set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
