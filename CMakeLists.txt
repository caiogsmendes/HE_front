cmake_minimum_required(VERSION 3.0.0)
project(gnss_execv VERSION 0.1.0 LANGUAGES C)

include(CTest)
enable_testing()

add_executable(gnss_execv execSys.c)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
