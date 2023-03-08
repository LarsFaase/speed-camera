PROJNAME=RSD_SpeedCamera

.PHONY: $(PROJNAME).pdf all clean

all: $(PROJNAME).pdf

$(PROJNAME).pdf: $(PROJNAME).tex
	mkdir -p out
	latexmk -pdflatex=lualatex -pdf -output-directory=out $<
	cp out/$(PROJNAME).pdf ../$(PROJNAME).pdf

cleanall:
	rm -rf out
	rm -f ../$(PROJNAME).pdf

clean:
	latexmk -pdflatex=lualatex -pdf -c -output-directory=out
