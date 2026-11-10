obj-m += ipu-bridge.o

KVER ?= $(shell uname -r)
KBUILD ?= /lib/modules/$(KVER)/build

all:
	$(MAKE) -C $(KBUILD) M=$(CURDIR) modules

clean:
	$(MAKE) -C $(KBUILD) M=$(CURDIR) clean
