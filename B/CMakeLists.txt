project(B)

add_executable(${PROJECT_NAME} main.cpp)

target_link_libraries(${PROJECT_NAME} A) #adding include directories of A to this project