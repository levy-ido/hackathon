cmake_minimum_required(VERSION 3.25)
project(tau_cs_hackathon_2023 C)

set(CMAKE_C_STANDARD 99)
add_executable(tau_cs_hackathon_2023 main.c)
target_link_libraries(tau_cs_hackathon_2023 ws2_32)