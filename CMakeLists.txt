cmake_minimum_required(VERSION 3.26.4)

project(EZEasing)

add_library(EZEasing STATIC)
target_sources(EZEasing PRIVATE
	"EZEasing.cpp"
	"EZEasing.hpp"
)
target_include_directories(EZEasing PUBLIC .)
