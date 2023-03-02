## BUILDING
all: build-rd build-rsd

build-rd:
	$(MAKE) -C ./RD_SpeedCamera all

build-rsd:
	$(MAKE) -C ./RSD_SpeedCamera all

## CLEANING NORMAL
clean: clean-rd clean-rsd

clean-rd:
	$(MAKE) -C ./RD_SpeedCamera clean

clean-rsd:
	$(MAKE) -C ./RSD_SpeedCamera clean

## CLEANING NORMAL
cleanall: cleanall-rd cleanall-rsd

cleanall-rd:
	$(MAKE) -C ./RD_SpeedCamera cleanall

cleanall-rsd:
	$(MAKE) -C ./RSD_SpeedCamera cleanall

## PHONY TARGETS
.PHONY: all build-rd build-rsd clean clean-rd clean-rsd cleanall cleanall-rd cleanall-rsd
