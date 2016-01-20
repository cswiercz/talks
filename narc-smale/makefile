talk=seattle-u

%.pdf : %.tex
	pdflatex $<

default: $(talk).pdf
	open $(talk).pdf

clean:
	-rm -f $(talk).{aux,log,nav,out,snm,toc,vrb}
	-rm -f ./*~

cleanall: clean
	-rm -f ./*.pdf
