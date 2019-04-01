# 指定生成目标 
add_executable(StartUseDll main.cpp)

# 添加头文件包含目录
# include_directories(${DIR_SRCS}/${Dll1})
# include_directories(${INCLUDE_DLL1})
# message("11111111111111111111111" ${INCLUDE_DLL1})
# include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../Dll1)
include_directories(../Dll1)

# 添加链接库
target_link_libraries(StartUseDll MathMultiply)
