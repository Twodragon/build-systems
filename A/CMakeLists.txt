project(A)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories (${PROJECT_NAME} INTERFACE ${PROJECT_SOURCE_DIR}/include)  # adding the lib.h file to include
