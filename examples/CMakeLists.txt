add_subdirectory(openpose)
add_subdirectory(actionpose)
add_subdirectory(tutorial_add_module)
add_subdirectory(tutorial_pose)
add_subdirectory(tutorial_thread)
add_subdirectory(tutorial_wrapper)
if (UNIX AND NOT APPLE)
  add_subdirectory(tests)
endif (UNIX AND NOT APPLE)
