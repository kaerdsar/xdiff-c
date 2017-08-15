project(xdiff)
add_executable(${PROJECT_NAME}
    XTree.cpp
    XHash.cpp
    XLut.cpp
    XParser.cpp
    XDiff.cpp
)
target_link_libraries(${PROJECT_NAME} xerces-c)
