CONFIG_SSTAR_CHIP_NAME := $(subst ",,$(CONFIG_SSTAR_CHIP_NAME))
EXTRA_CFLAGS += -Idrivers/sstar/include

obj-y += ms_composite_clk.o
obj-$(CONFIG_MS_USCLK)=ms_usclk.o
obj-y += $(CONFIG_SSTAR_CHIP_NAME)/
