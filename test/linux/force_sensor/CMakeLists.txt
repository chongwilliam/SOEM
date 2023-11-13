
set(SOURCES force_sensor.c)
add_executable(force_sensor ${SOURCES})
target_link_libraries(force_sensor soem hiredis)
install(TARGETS force_sensor DESTINATION bin)
