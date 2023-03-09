# Author: Justin Wade, Aaron Linneman, Jackson Pawlowicz (with numeorus online sources)

cmake_minimum_required(VERSION 3.0.0)

project(Virtual_Synth_Project_JW_AL_JP VERSION 0.1.0 DESCRIPTION "A first synth project")
include_directories("include/")
add_executable(go.exe main.cpp)

# Note: "#" will comment out a line of a text document