.PHONY: all ds ds-clean

all: ds ds-clean pc pc-clean wii wii-clean linux linux-clean psp psp-clean

ds:
	$(MAKE) -C ./Makefiles -f makefile_ds

ds-clean:
	$(MAKE) -C ./Makefiles -f makefile_ds clean

pc:
	$(MAKE) -C ./Makefiles -f makefile_pc

pc-clean:
	$(MAKE) -C ./Makefiles -f makefile_pc clean

wii:
	$(MAKE) -C ./Makefiles -f makefile_rvl

wii-clean:
	$(MAKE) -C ./Makefiles -f makefile_rvl clean

linux:
	$(MAKE) -C ./Makefiles -f makefile_linux

linux-clean:
	$(MAKE) -C ./Makefiles -f makefile_linux clean

psp:
	$(MAKE) -C ./Makefiles -f makefile_psp

psp-clean:
	$(MAKE) -C ./Makefiles -f makefile_psp clean
