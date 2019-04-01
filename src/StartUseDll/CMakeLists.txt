# 指定生成目标 
add_executable(StartUseDll main.cpp)

# 添加头文件包含目录
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../Dll1)

# 添加链接库
target_link_libraries(StartUseDll MathMultiply)
