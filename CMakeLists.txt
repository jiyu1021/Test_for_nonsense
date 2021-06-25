project(hello_word)
aux_source_directory(. DIR_TOOT_SRCS)
set (CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} -g")
add_executable(hello_word ${DIR_TOOT_SRCS})
