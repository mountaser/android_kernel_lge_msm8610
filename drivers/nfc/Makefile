KERNELRELEASE ?= $(shell uname -r)
BUILD_KERNEL_PATH ?= /lib/modules/$(KERNELRELEASE)/build
INSTALL_MOD_PATH ?= $(INSTALL_PATH)/lib/modules/$(KERNELRELEASE)
INSTALL_PN5XX_I2C_PATH ?= $(INSTALL_MOD_PATH)/kernel/drivers/nfc

obj-$(CONFIG_NFC_NXP_PN5XX)	+= pn5xx_i2c.o
obj-$(CONFIG_LGE_NFC_PN547_C2)  := pn547_lge.o		
obj-$(CONFIG_LGE_NFC_PN547_C2)  += pn547_lge_hwadapter.o
