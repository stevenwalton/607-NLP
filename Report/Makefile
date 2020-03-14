SRC :=$(wildcard *.tex *.bib)

Summary.pdf: $(SRC)
	pdflatex Summary.tex

clean:
	rm -f *.glo *.log *.dvi *.gls *.toc *.aux *.ist *.out *.glg *.pdf *.bbl *.blg *.lof *.brf

.PHONY: clean
