cmake_minimum_required(VERSION 3.10)

project(LeranCmake)

message(STATUS "********CMake version: ${CMAKE_VERSION}********")  # CMAKE_VERSION宏表示当前cmake版本
message(STATUS "********CMake generator: ${CMAKE_GENERATOR}********")  # CMAKE_GENERATOR宏表示当前cmake生成器 
message(STATUS "********CMake build type: ${CMAKE_BUILD_TYPE}********")  # CMAKE_BUILD_TYPE宏表示当前cmake构建类型
message(STATUS "********CMake source dir: ${CMAKE_SOURCE_DIR}********")  # CMAKE_SOURCE_DIR宏表示当前cmake根源代码目录
message(STATUS "********CMake project source dir: ${PROJECT_SOURCE_DIR}********") # PROJECT_SOURCE_DIR宏表示工程顶层目录
message(STATUS "********CMake binary dir: ${CMAKE_BINARY_DIR}********")  # CMAKE_BINARY_DIR宏表示当前cmake二进制目录，运行cmake目录。外部构建时就是bulid目录
message(STATUS "********CMake current source dir: ${CMAKE_CURRENT_SOURCE_DIR}********")  # CMAKE_CURRENT_SOURCE_DIR宏表示当前处理CM艾克Lists.txt所在目录  
message(STATUS "********CMake current binary dir: ${CMAKE_CURRENT_BINARY_DIR}********")  # CMAKE_CURRENT_BINARY_DIR宏表示当前cmake二进制目录（The bulid directory you are currently in.当前所在build目录）
message(STATUS "********CMake module path: ${CMAKE_MODULE_PATH}********")  # CMAKE_MODULE_PATH宏表示当前cmake模块路径
message(STATUS "********CMake install prefix: ${CMAKE_INSTALL_PREFIX}********")  # CMAKE_INSTALL_PREFIX宏表示当前cmake安装前缀路径
# CMAKE_CXX_FLAGS  该宏表示C++编译选项设置
# CMAKE_CXX_FLAGS_DEBUG 该宏表示C++编译选项设置（Debug模式）
# CMAKE_CXX_FLAGS_RELEASE 该宏表示C++编译选项设置（Release模式）
# CMAKE_CXX_FLAGS_MINSIZEREL 该宏表示C++编译选项设置（MinSizeRel模式）
# CMAKE_CXX_FLAGS_RELWITHDEBINFO 该宏表示C++编译选项设置（RelWithDebInfo模式）
# CMAKE_C_FLAGS 该宏表示C编译选项设置
# CMAKE_C_FLAGS_DEBUG 该宏表示C编译选项设置（Debug模式）
# CMAKE_C_FLAGS_RELEASE 该宏表示C编译选项设置（Release模式
# CMAKE_C_FLAGS_MINSIZEREL 该宏表示C编译选项设置（MinSizeRel模式）
# CMAKE_C_FLAGS_RELWITHDEBINFO 该宏表示C编译选项设置（RelWithDebInfo模式）
# CMAKE_CXX_COMPILER 该宏表示C++编译器路径
# CMAKE_C_COMPILER 该宏表示C编译器路径




add_subdirectory(src)