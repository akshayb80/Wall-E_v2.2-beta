# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly

cmake_minimum_required(VERSION 3.5)

set(EXTRA_COMPONENT_DIRS $ENV{HOME}/Wall-E_v2.1/components)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)

project(mpu_test)
