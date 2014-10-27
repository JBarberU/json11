cmake_minimum_required(VERSION 2.8)

set(CMAKE_CXX_FLAGS "-O -std=c++11 -stdlib=libc++ -fno-rtti -fno-exceptions")

set(SRC
	json11.cpp
) 

set(HEADERS
	json11.hpp
)

add_library(dropbox_json "${SRC}")

