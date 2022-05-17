set(CMAKE_CXX_STANDARD 20)
# set project name
project(Plus20 VERSION 1.0)

# add header and source files
list(APPEND SOURCE_SUFFIX "*.hpp" "*.h" "*.cc" "*.inl")
file(GLOB_RECURSE SOURCE "./" ${SOURCE_SUFFIX})

add_executable(${PROJECT_NAME} ${SOURCE})
