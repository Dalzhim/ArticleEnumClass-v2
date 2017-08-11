cmake_minimum_required(VERSION 2.8)

project(EnumClass)

add_executable(enumclass main.cpp)
target_compile_features(enumclass PRIVATE cxx_constexpr cxx_relaxed_constexpr)
