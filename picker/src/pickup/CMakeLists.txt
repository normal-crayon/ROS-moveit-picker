add_executable(pickup src/pickup.cpp)
target_link_libraries(pickup ${catkin_LIBRARIES} ${Boost_LIBRARIES})
install(TARGETS pickup DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
