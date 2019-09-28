PAPER = main
TEX = $(wildcard *.tex)

.PHONY: all clean

$(PAPER).pdf: $(TEX)
	xelatex $(PAPER)

clean:
	rm -f *.aux *.bbl *.blg *.log *.out $(PAPER).pdf *.dvi *.ps *.toc

