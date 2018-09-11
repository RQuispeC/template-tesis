all:
	pdflatex tesis
	bibtex tesis
	pdflatex tesis
	
clean:
	rm -f *.aux *.bbl *.log *.blg *.dvi tesis.toc

cleanall: clean
	rm -f tesis.pdf
