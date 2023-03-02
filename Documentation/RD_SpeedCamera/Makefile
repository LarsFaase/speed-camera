PROJNAME=RD_SpeedCamera

ifdef OS
    RMDIR = rmdir /s /q
else
    RMDIR = rm -rf
endif

.PHONY: $(PROJNAME).pdf all clean

all: $(PROJNAME).pdf

$(PROJNAME).pdf: $(PROJNAME).tex
	-mkdir out
	latexmk -pdflatex=lualatex -pdf -output-directory=out $<
	cp out/$(PROJNAME).pdf ../$(PROJNAME).pdf

cleanall:
	latexmk -pdflatex=lualatex -pdf -C -output-directory=out
	$(RMDIR) out

clean:
	latexmk -pdflatex=lualatex -pdf -c -output-directory=out
