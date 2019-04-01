# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)

# 项目信息
project (StartUseDll)

# 查找当前目录下的所有源文件
# 并将名称保存到 DIR_SRCS 变量
aux_source_directory(. DIR_SRCS)

# 添加子目录
add_subdirectory(StartUseDll)
add_subdirectory(Dll1)

set(INCLUDE_DLL1 ${CMAKE_CURRENT_SOURCE_DIR}/Dll1)
