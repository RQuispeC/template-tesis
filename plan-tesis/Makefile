all:
	pdflatex plan
	bibtex plan
	pdflatex plan

clean:
	rm -f *.aux *.bbl *.log *.blg *.dvi plan.toc

cleanall: clean
	rm -f plan.pdf
