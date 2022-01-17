.PHONY: all library binary clean

all: library binary

library:
	$(MAKE) -C ./library all

binary:
	$(MAKE) -C ./program all

clean: 
	$(MAKE) -C ./program clean
	$(MAKE) -C ./library clean
