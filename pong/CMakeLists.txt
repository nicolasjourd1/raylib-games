set(HEADERS)

set(SOURCES src/pong.cpp)

add_executable(pong ${SOURCES} ${HEADERS})

target_include_directories(pong PUBLIC include)

target_link_libraries(pong PRIVATE raylib)
