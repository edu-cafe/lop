##
## CMakeLists.txt : for Executable App. Programming
##
##              Kim Soo Hyun(@")
##
PROJECT ( "Executable App. Build Project" LANGUAGES C )
CMAKE_MINIMUM_REQUIRED ( VERSION 3.10 )
SET ( CMAKE_BUILD_TYPE Debug )
#SET ( CMAKE_VERBOSE_MAKEFILE false )
MESSAGE ( STATUS ${CMAKE_PROJECT_NAME} )

ADD_EXECUTABLE(mytest test1.c test2.c test3.c)
