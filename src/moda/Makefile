CC = gcc
ROOT := $(shell pwd)/..
INCLUDE := $(ROOT)/include

CFLAGS +=-I$(INCLUDE)

target:moda
moda:moda.o
	$(CC) -o moda moda.o
moda.o:moda.c
	$(CC) $(CFLAGS) -c moda.c

.PHONY:clean
clean:
	-rm *.o moda
