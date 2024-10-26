cmake_minimum_required(VERSION 3.5)

idf_component_register(
                       SRCS "CH9120.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino
)

project(CH9120)
