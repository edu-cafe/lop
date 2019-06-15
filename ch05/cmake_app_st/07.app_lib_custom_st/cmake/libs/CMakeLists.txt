##
## CMakeLists.txt : for Static/Shared/Dynamic Library Programming
##
##		Kim Soo Hyun(@")
##
PROJECT ( "Static/Shared Library Build" LANGUAGES C )
CMAKE_MINIMUM_REQUIRED ( VERSION 3.10 )
SET ( CMAKE_BUILD_TYPE Release )
#SET ( CMAKE_VERBOSE_MAKEFILE true )
MESSAGE ( ${CMAKE_PROJECT_NAME} )

SET ( LIBA_PATH "../libStatic/" )
SET ( LIBS_PATH "../libShared/" )
SET ( LIB_NAME libmytest )

...........


