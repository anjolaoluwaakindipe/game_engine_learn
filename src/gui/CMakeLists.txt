add_executable(gui gui.cpp)
target_link_libraries(gui PRIVATE engine)
target_link_libraries(gui PRIVATE graphics)
