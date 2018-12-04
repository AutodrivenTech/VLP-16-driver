ADD_EXECUTABLE(udp_server udp_server.cpp)
TARGET_LINK_LIBRARIES(udp_server ${Boost_LIBRARIES})

ADD_EXECUTABLE(udp_client udp_client.cpp)
TARGET_LINK_LIBRARIES(udp_client ${Boost_LIBRARIES})




#ADD_EXECUTABLE(kittitrackletextract kittitrackletextract.cpp ${CMAKE_SOURCE_DIR}/include/tracklets.h)
#TARGET_LINK_LIBRARIES(kittitrackletextract ${Boost_LIBRARIES} ${PCL_LIBRARIES})

