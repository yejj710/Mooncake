add_executable(store_py_test store_py_test.cpp)
target_link_libraries(store_py_test PUBLIC transfer_engine gtest gtest_main)
add_test(NAME store_py_test COMMAND store_py_test)

