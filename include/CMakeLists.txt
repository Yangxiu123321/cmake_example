# install header
install(
  DIRECTORY
    ${CMAKE_CURRENT_SOURCE_DIR}/
  DESTINATION
    ${INSTALL_INCLUDEDIR}/
  COMPONENT
    dev
  FILES_MATCHING
    PATTERN "*.h"
  )
