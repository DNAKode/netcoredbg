cmake_minimum_required(VERSION 3.5)

project(elf++)

add_library(
  elf++
  STATIC
  elf.cpp
  mmap_loader.cpp
  to_string.cpp
)

