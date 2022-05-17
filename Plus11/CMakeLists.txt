# set cpp standard version
set(CMAKE_CXX_STANDARD 11)

project(Plus11 VERSION 1.0)

list(APPEND SOURCE_SUFFIX "*.hpp" "*.h" "*.cc" "*.inl")
file(GLOB_RECURSE SOURCE "./" ${SOURCE_SUFFIX})

add_executable(${PROJECT_NAME} ${SOURCE})