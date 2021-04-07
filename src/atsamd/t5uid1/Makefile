# T5UID1 samd build rules

dirs-$(CONFIG_T5UID1_SERIAL) += src/atsamd/t5uid1 src/generic/t5uid1

t5uid1-src-y := atsamd/t5uid1/serial.c
t5uid1-src-$(CONFIG_MACH_SAMD51) := atsamd/t5uid1/samd51_serial.c
src-$(CONFIG_T5UID1_SERIAL) += $(t5uid1-src-y) generic/t5uid1/serial_irq.c
