COINES_INSTALL_PATH ?= ../../../..

EXAMPLE_FILE ?= aux_fifo_watermark_header_mode.c

API_LOCATION ?= ../..

COMMON_LOCATION ?= ..

BMM150_SOURCE ?= ../../../bmm150

C_SRCS += \
$(API_LOCATION)/bmi2.c \
$(API_LOCATION)/bmi270_legacy.c \
$(BMM150_SOURCE)/bmm150.c \
$(COMMON_LOCATION)/common/common.c

INCLUDEPATHS += \
$(API_LOCATION) \
$(BMM150_SOURCE) \
$(COMMON_LOCATION)/common 

TARGET = MCU_APP30

include $(COINES_INSTALL_PATH)/coines.mk