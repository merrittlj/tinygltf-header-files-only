set(LIBRARY_INCLUDE_DIR "${CMAKE_CURRENT_SOURCE_DIR}/include/")

add_library(tinygltf INTERFACE)  # this is an header-only library.

target_include_directories(tinygltf INTERFACE ${LIBRARY_INCLUDE_DIR})
