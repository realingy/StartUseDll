# 指定生成目标 
#ADD_EXECUTABLE(StartUseDll main.cpp)
add_library(StartUseDll UseMultip.cpp)
# add_library(StartUseDll UseMultip.cpp)

# 添加头文件包含目录
INCLUDE_DIRECTORIES(${PROJECT_SOURCE_DIR}/Dll1)

# 添加链接库
TARGET_LINK_LIBRARIES(StartUseDll MathMultiply)
