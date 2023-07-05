cmake_minimum_required(VERSION 3.10)
project(cpp-basic)

# 添加可执行文件并指定源代码文件
add_executable(my_executable head/main.cpp head/ListNode.cpp concurrent/concurrent2.cpp)

# 设置 C++ 编译选项
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-Wall")

# 添加头文件搜索路径
include_directories(head)

# 添加库文件搜索路径（如果有的话）
# link_directories()

# 添加依赖库（如果有的话）
# find_package()

# 链接库文件（如果有的话）
# target_link_libraries()

# 安装目标文件和头文件（如果需要安装的话）
# install()