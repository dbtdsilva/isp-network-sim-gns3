docname = proj2

all: 	$(docname).pdf

$(docname).aux: 	$(docname).tex
	pdflatex $(docname).tex
	pdflatex $(docname).tex

#$(docname).bbl: 	$(docname).bib
#	bibtex $(docname)

#$(docname).gls: 
#	makeglossaries $(docname)

$(docname).pdf: 	$(docname).aux 
		#$(docname).bbl 
		#$(docname).gls 
	pdflatex $(docname).tex
	pdflatex $(docname).tex

clean:	
	rm -f *.aux *.lof *.log *.toc *.lot *.blg *.bbl *.gls *.glg *.glo *.out *.acr *.acn *.alg *.dvi *.out *.ist
