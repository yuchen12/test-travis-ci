set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR})
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR})

add_library(helloworld hello.cc world.cc)

add_executable(foo main.cc)
target_link_libraries(foo helloworld)
