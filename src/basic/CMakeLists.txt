set(target_name basic)
add_library(${target_name} STATIC "")
target_sources(${target_name} PRIVATE "${PROJECT_SOURCE_DIR}/src/basic/message.cpp" PRIVATE "${PROJECT_SOURCE_DIR}/include/basic/message.h")