# add the executable
add_executable(simulation simulation_main.cc)
target_link_libraries(simulation planner glog gflags)
