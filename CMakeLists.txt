cmake_minimum_required(VERSION 3.10)
project(MyCppApp)

set(CMAKE_CXX_STANDARD 17)

add_executable(app src/main.cpp)

# Boost (通信)
find_package(Boost REQUIRED COMPONENTS system)

target_link_libraries(app PRIVATE Boost::system)
