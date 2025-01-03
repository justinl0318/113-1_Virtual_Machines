obj-m = virt_walker.o
PWD := $(shell pwd)
EXTRA_CFLAGS = -Wall -g

all:
	$(MAKE) -C $(KDIR) M=$(PWD) modules

clean:
	$(MAKE) -C $(KDIR) M=$(PWD) clean
