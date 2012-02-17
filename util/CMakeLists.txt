add_executable(parse
	EXCLUDE_FROM_ALL
	parse.cpp)
target_link_libraries(parse yaml-cpp)
