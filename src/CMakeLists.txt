# Production targets.
set (SOURCES
    ${CMAKE_CURRENT_SOURCE_DIR}/KVApp/main.cpp
)

add_executable(KVApp)

target_sources(KVApp PRIVATE ${SOURCES})    