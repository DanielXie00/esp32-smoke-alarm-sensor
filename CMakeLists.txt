cmake_minimum_required(VERSION 3.5)

set(MAIN_SRCS main/main.c)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(esp32-smoke-alarm)
