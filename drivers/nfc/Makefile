#
# Makefile for nfc devices
#

obj-$(CONFIG_LGE_NFC_PN547_C2)	:= pn547_lge.o
obj-$(CONFIG_LGE_NFC_PN547_C2)	+= pn547_lge_hwadapter.o
obj-$(CONFIG_NFC_BCM2079X)	+= bcm2079x.o

ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG
