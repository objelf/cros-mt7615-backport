#SPDX-License-Identifier: ISC

obj-$(CONFIG_MT7615E) += mt7615e.o

CFLAGS_trace.o := -I$(src)

mt7615e-y := pci.o pci_init.o pci_mac.o init.o dma.o eeprom.o main.o mcu.o mac.o mmio.o \
	     debugfs.o trace.o
