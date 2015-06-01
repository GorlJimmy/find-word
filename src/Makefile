CC = gcc

ROOT := $(shell pwd)
INCLUDE :=$(ROOT)/include

SRC := $(ROOT)
SUB_DIR := $(SRC)/moda $(SRC)/modb
default:usr
usr:
	@for n in $(SUB_DIR); do $(MAKE) -C $$n ; done

.PHONY:clean
clean:
	@for n in $(SUB_DIR); do $(MAKE) -C $$n clean; done
