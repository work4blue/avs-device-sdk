cmake_minimum_required(VERSION 3.1 FATAL_ERROR)

set(INCLUDE_PATH
    "${Notifications_INCLUDE_DIRS}"
    "${AVSCommon_SOURCE_DIR}/AVS/test")

discover_unit_tests("${INCLUDE_PATH}" "Notifications;UtilsCommonTestLib;SDKInterfacesTests")
