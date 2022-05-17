cmake_minimum_required(VERSION 3.10)

project(Plus11)
project(Plus14)
project(Plus17)
project(Plus20)
project(Plus23)

set(bin_dir "${CMAKE_SOURCE_DIR}/output/bin")
set(lib_dir "${CMAKE_SOURCE_DIR}/output/lib")

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${bin_dir})
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${lib_dir})

# cpp11
add_subdirectory(Plus11)

# cpp14
add_subdirectory(Plus14)

# cpp17
add_subdirectory(Plus17)

# cpp20
add_subdirectory(Plus20)

