# cmake_minimum_required(VERSION <specify CMake version here>)
project(File_system_simulator)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)
include_directories(bin)
include_directories(cmake-build-debug)
include_directories(obj)

add_executable(File_system_simulator
    .idea/codeStyles/Project.xml
    ".idea/File system simulator.iml"
    .idea/misc.xml
    .idea/modules.xml
    .idea/workspace.xml
    "bin/Debug/File system simulator.exe"
    obj/Debug/main.o
    CMakeLists.txt
    "File system simulator.cbp"
    "File system simulator.depend"
    "File system simulator.layout"
    main.c)
