add_library(formatter_ex STATIC formatter_ex.cpp) 
target_include_directories(formatter_ex PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries(formatter_ex formatter)
