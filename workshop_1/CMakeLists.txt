cmake_minimum_required(VERSION 3.16 FATAL_ERROR)
project(workshop_1)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SFML_DIR "C:/SFML/SFML-3.0.2/lib/cmake/SFML")
set(SFML_STATIC_LIBRARIES TRUE)

find_package(SFML 3 COMPONENTS Graphics Window System REQUIRED)

add_subdirectory(workshop_1_1)
add_subdirectory(workshop_1_2)
add_subdirectory(workshop_1_3)
add_subdirectory(workshop_1_4)
