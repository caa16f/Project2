obj-m := init_carry_items.o

PWD := $(shell pwd)
KDIR := /lib/modules/`uname -r`/build

default:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) modules

clean:
	rm -f *.o *.ko *.mod.* Module.* modules.*
