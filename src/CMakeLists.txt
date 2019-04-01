# CMake 最低版本号要求
CMAKE_MINIMUM_REQUIRED (VERSION 3.6)

# 项目信息
PROJECT (StartUseDll)

# 查找当前目录下的所有源文件
# 并将名称保存到 DIR_SRCS 变量
AUX_SOURCE_DIRECTORY(. DIR_SRCS)

# 添加子目录
ADD_SUBDIRECTORY(StartUseDll)
ADD_SUBDIRECTORY(Dll1)
