file(GLOB plannerlibs planner/*.cc)


add_library(planner ${plannerlibs})
set_target_properties(planner PROPERTIES LINKER_LANGUAGE CXX)


# add the executable
add_executable(playground playground_main.cc)
target_link_libraries(playground planner glog gflags)
