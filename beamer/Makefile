pdf all: beamerTemplate.pdf

beamerTemplate.pdf: beamerTemplate.dvi
	dvipdf beamerTemplate.dvi

beamerTemplate.dvi: beamerTemplate.tex 
	latex beamerTemplate.tex
	latex beamerTemplate.tex

clean:
	rm -f beamerTemplate.out
	rm -f beamerTemplate.dvi
	rm -f beamerTemplate.log
	rm -f beamerTemplate.aux
	rm -f beamerTemplate.nav
	rm -f beamerTemplate.snm
	rm -f beamerTemplate.toc
	rm -f beamerTemplate.pdf
