# 查找当前目录下的所有源文件
# 并将名称保存到 DIR_LIB_SRCS 变量
# aux_source_directory(. DIR_LIB_SRCS)

SET(SOURCE_FILES Dll1.cpp Dll1.h)

# 生成链接库
# ADD_LIBRARY (MathMultiply SHARED ${SOURCE_FILES})
ADD_LIBRARY (MathMultiply ${SOURCE_FILES})
