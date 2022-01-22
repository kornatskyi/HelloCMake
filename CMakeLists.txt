cmake_minimum_required(VERSION "3.16.3" )

project(HelloCMake)

 include_directories(${PROJECT_SOURCE_DIR}/include)
 add_executable(app src/main.cpp src/foo.cpp)

 