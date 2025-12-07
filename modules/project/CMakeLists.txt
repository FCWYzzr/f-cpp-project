project(project)

add_executable(project)
configure_target(project)
target_link_libraries(project PRIVATE f)
