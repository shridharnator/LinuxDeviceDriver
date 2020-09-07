

obj-m := chr_drv_exl.o

KDIR :=$PWD
PWD := $(shell pwd)
default:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) modules
install:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) module_install
clean:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) clean
