#CFLAGS += -DSTARTUP_NO_IRQS
CXXFLAGS += -I.
ISPOPTS += -t
LINK = LPC810.ld
ARCH = lpc8xx

OBJS = rf_ook.o system_LPC8xx.o gcc_startup_lpc8xx.o \
		uart.o printf.o printf-retarget.o

default: isp

SHARED = ../sys-none
include $(SHARED)/rules.mk
