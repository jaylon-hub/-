cmake_minimum_required(VERSION 3.21)
project(_github)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(_github
        .idea/.gitignore
        .idea/modules.xml
        .idea/vcs.xml
        .idea/workspace.xml
        .idea/���ݽṹ-github.iml
        .gitignore
        LICENSE
        README.md
        sequence.cpp)
