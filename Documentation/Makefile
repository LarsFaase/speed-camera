SUBDIRS := $(wildcard */.)

all: $(SUBDIRS)
$(SUBDIRS):
	$(MAKE) -C $@

clean:
	rm *.pdf

.PHONY: all clean $(SUBDIRS)
