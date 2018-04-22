cmake_minimum_required (VERSION 2.8)
project (PongTracker)

include_directories ("$ENV{OPENNI2_INCLUDE}")
link_directories("$ENV{OPENNI2_REDIST}")

file(COPY "${CMAKE_CURRENT_SOURCE_DIR}/config/OpenNI.ini" DESTINATION "${CMAKE_CURRENT_BINARY_DIR}")

add_executable(pongtracker main.cpp)

target_link_libraries(pongtracker OpenNI2)