include_directories(${CMAKE_SOURCE_DIR}/src ${CMAKE_BINARY_DIR}/src ${LIBEV_INCLUDE_DIR})

add_executable(example example.c)
target_link_libraries(example uwsc ${LIBEV_LIBRARY})
