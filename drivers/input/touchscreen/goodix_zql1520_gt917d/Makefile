#
# Makefile for the input core drivers.
#
EXTRA_CFLAGS += $(call cc-disable-warning, date-time)

obj-$(CONFIG_TOUCHSCREEN_GT917D_ZQL1520) += goodix_ts.o

goodix_ts-objs := gt9xx.o
goodix_ts-objs += gt9xx_update.o
goodix_ts-objs += goodix_tool.o
