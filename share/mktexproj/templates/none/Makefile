
TEX = latexmk -pdflua -outdir=Output

.PHONY: all clean

all: >>>FILENAME<<<.pdf

%.pdf: %.tex
	$(TEX) $<
	cp Output/$@ ./

clean:
	rm -rf Output
	rm  -f >>>FILENAME<<<.pdf

