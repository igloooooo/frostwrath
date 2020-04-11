AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/Reforger.cpp")
AC_ADD_SCRIPT_LOADER("Reforging" "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/reforging.conf.dist")
