cmake_minimum_required(VERSION 3.1)

add_library(string_view INTERFACE)

install(DIRECTORY "single_include/bpstd/" DESTINATION "string_view/include/")
