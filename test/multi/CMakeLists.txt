PROJECT(test_fib)

SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${LIBCPU_RUNTIME_OUTPUT_DIRECTORY})
ADD_EXECUTABLE(test_fib fib.cpp)
TARGET_LINK_LIBRARIES(test_fib cpu)
