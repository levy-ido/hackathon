cmake_minimum_required(VERSION 3.25)
project(tau_cs_hackathon C)

set(CMAKE_C_STANDARD 99)
add_executable(hackathon main.c)
target_link_libraries(hackathon ws2_32)