cmake_minimum_required(VERSION 3.10)
project(planning
    VERSION 0.1.0
    DESCRIPTION "a demo of cmake planning"
    HOMEPAGE_URL "https://github.com/zjy20376004/cmake_planning_demo"
    LANGUAGES CXX

)
set(CMAKE_CXX_STANDARD 17)
# 变量和目录设置
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
set(Process_Dir ${CMAKE_SOURCE_DIR}/src/process)
set(Pnc_Map_Dir ${CMAKE_SOURCE_DIR}/src/pnc_map)
# 添加子目录
add_subdirectory(src)