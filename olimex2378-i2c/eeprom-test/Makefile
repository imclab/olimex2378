
#
# Makefile for eeprom-test
#

NAME            := eeprom-test
LPCLIBDIR       := ../../liblpc23xx
LIBDIR          := ../..

INCLUDE         := -I.\
                   -I./include\
                   -I$(LPCLIBDIR)/include\
                   -I$(LPCLIBDIR)/lpc23xx-uart/include\
                   -I$(LPCLIBDIR)/lpc23xx-binsem/include\
                   -I$(LPCLIBDIR)/lpc23xx-i2c/include\
                   -I$(LPCLIBDIR)/lpc23xx-util/include\
                   -I$(LPCLIBDIR)/lpc23xx-pll/include\
                   -I$(LPCLIBDIR)/lpc23xx-vic/include\
                   -I$(LIBDIR)/olimex2378-util/include

DEBUG           := -DDEBUG_I2C
include $(LIBDIR)/include/common-test-make.mk


