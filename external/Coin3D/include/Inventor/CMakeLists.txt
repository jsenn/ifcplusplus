add_subdirectory(C)
add_subdirectory(system)
file(GLOB_RECURSE HDRS *.h)
set(COIN_DOCUMENTATION_FILES
	${COIN_DOCUMENTATION_FILES}
	${HDRS}
	CACHE INTERNAL "COIN_DOCUMENTATION_FILES"
)
