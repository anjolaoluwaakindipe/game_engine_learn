add_executable(gui WIN32 gui.cpp)
target_link_libraries(gui PRIVATE engine)
target_link_libraries(gui PRIVATE graphics)
target_link_libraries(gui PRIVATE wx::core wx::base)
