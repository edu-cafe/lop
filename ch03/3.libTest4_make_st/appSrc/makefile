##
## Makefile : for Static/Shared/Dynamic Library Programming
##
##		Kim Soo Hyun(@")
##

PLATFORM = 

INC_PATH = ../include
CC = $(PLATFORM)gcc
CFLAGS = -Wall -O2 -I$(INC_PATH)
LIB_PATH_STATIC = ../libStatic
LIB_PATH_SHARED = ../libShared

APP = app
APP_ALL = app_static app_shared

all : $(APP_ALL)

app_static : $(APP).o
	@echo "app create using static library...."
	_____________
	$(CC) -o $@ $(APP).o -L $(LIB_PATH_STATIC) -ltest

app_shared : $(APP).o
	@echo "app create using shared library...."
	______________
	$(CC) -o $@ $(APP).o -L $(LIB_PATH_SHARED) -ltest

clean :
	_____________
	_____________
	-rm -f $(APP_ALL) $(APP).o
	