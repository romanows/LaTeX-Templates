# Make sure a newline immediately follows the base filename of the .tex file, below
BASE = beamerTemplate

pdf all: $(BASE).pdf

%.pdf: %.dvi
	dvipdf $(BASE).dvi

%.dvi: %.tex 
	latex $(BASE).tex
	latex $(BASE).tex

clean:
	rm -f $(BASE).out
	rm -f $(BASE).dvi
	rm -f $(BASE).log
	rm -f $(BASE).aux
	rm -f $(BASE).nav
	rm -f $(BASE).snm
	rm -f $(BASE).toc
	rm -f $(BASE).pdf
