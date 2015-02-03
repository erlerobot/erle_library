add_subdirectory (${CMAKE_CURRENT_SOURCE_DIR}/stable)

IF(TESTING)
	add_subdirectory (${CMAKE_CURRENT_SOURCE_DIR}/testing ${CMAKE_CURRENT_SOURCE_DIR}/testing)
ENDIF()
