install.pdf: install.sgm
	openjade -t tex -V tex-backend -d docbook.dsl install.sgm
	pdfjadetex install.tex
	pdfjadetex install.tex
	pdfjadetex install.tex

clean:
	-rm -f *.out *.aux *.log *.dvi
