
ADD_DEFINITIONS(-DTHIS_SOURCE_DIR="${CMAKE_CURRENT_SOURCE_DIR}")

ADD_EXECUTABLE(openMVG_sample_describe_and_match describe_and_match.cpp)
TARGET_LINK_LIBRARIES(openMVG_sample_describe_and_match
  ${OpenMVG_LIBRARIES})

SET_PROPERTY(TARGET openMVG_sample_describe_and_match PROPERTY FOLDER OpenMVG/Samples)
