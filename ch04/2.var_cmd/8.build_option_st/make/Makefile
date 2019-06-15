OBJS = test1.o test2.o test3.o

INC_DIR = $$PWD/include
CFLAGS = -DNO1=10 -DNO2=20 -Wall -g -O2 -I${INC_DIR}
LDFLAGS = -static

mytest: $(OBJS)
	$(CC) -o $@ $^ $(LDFLAGS)

test1.o: test1.c
test2.o: test2.c
test3.o: test3.c

clean:
	rm $(OBJS) mytest
	
