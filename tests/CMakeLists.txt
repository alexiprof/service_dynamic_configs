include(UserverTestsuite)

userver_testsuite_add(
  NAME service_template-testsuite
  REQUIREMENTS ${CMAKE_CURRENT_SOURCE_DIR}/requirements.txt
  WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}
)
