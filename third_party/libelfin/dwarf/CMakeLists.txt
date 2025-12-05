cmake_minimum_required(VERSION 3.5)

project(dwarf++)

add_library(
  dwarf++
  STATIC
  abbrev.cpp
  attrs.cpp
  cursor.cpp
  die.cpp
  die_str_map.cpp
  dwarf.cpp
  elf.cpp
  expr.cpp
  line.cpp
  rangelist.cpp
  to_string.cpp
  value.cpp
)

