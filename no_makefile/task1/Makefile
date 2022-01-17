.PHONY: all library binary clean

all: library binary

library:
	$(MAKE)	-C ./lib all

binary:
	$(MAKE) -C ./src all

clean:
	$(MAKE) -C ./src clean
	$(MAKE) -C ./lib clean
