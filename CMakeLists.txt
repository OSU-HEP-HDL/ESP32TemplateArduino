cmake_minimum_required(VERSION 3.16.0)

set(PROJECT_NAME
    ESP32TemplateArduino
)
set(SOURCE_DIR
    src
)
set(SOURCE
    ${SOURCE_DIR}/main.cpp
)
# set(LIBRARIES_DIR
#     lib
# )
# set(LIBRARIES 
#     Template
# )

# include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(${ROJECT_NAME})

###########
# Project #
###########
add_executable(${PROJECT_NAME} ${SOURCE})

# foreach(LIBRARY ${LIBRARIES})
#     add_subdirectory("${LIBRARIES_DIR}/${LIBRARY}")
# endforeach(LIBRARY)
# target_link_libraries(${PROJECT_NAME} ${LIBRARIES})