SRCS1 = test1.c test2.c test3.c
SRCS2 = exam2.c test2.c
SRCS3 = exam3.c test3.c

OBJS1 = $(SRCS1:.c=.o)
OBJS2 = $(SRCS2:.c=.o)
OBJS3 = $(SRCS3:.c=.o)

SRCS = $(wildcard *.c)
OBJS = $(SRCS:.c=.o)

TARGET1 = exam1
TARGET2 = exam2
TARGET3 = exam3

all: $(TARGET1) $(TARGET2) $(TARGET3)


$(TARGET1): $(OBJS1)
	$(CC) -o $@ $^

$(TARGET2): $(OBJS2)
	$(CC) -o $@ $^

$(TARGET3): $(OBJS3)
	$(CC) -o $@ $^

test1.o: test1.c a.h b.h
test2.o: test2.c a.h c.h
test3.o: test3.c a.h b.h c.h
exam2.o: exam2.c a.h b.h
exam3.o: exam2.c a.h c.h

clean : 
	-rm $(OBJS)
	-rm $(TARGET1) $(TARGET2) $(TARGET3)

