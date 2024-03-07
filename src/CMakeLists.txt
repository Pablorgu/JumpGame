project(JumpGame)

add_executable(JumpGame main.cpp)
target_link_libraries(JumpGame glfw)
target_include_directories(JumpGame PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../include)