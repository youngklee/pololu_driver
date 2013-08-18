set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
add_executable(pololu_driver src/pololu_driver.cpp)
target_link_libraries(pololu_driver usb-1.0)
