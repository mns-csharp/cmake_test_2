#!cmake_test/src/models
add_executable(main main.cpp main.h)


target_link_libraries(main # target lib
  PRIVATE # cannot be accessed from outside world
        Initial # to be linked li
  )

#target_include_directories(main PUBLIC ${CMAKE_CURRENT_LIST_DIR} )
target_include_directories(main
        PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
        )