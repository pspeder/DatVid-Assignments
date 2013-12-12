build:
	pdflatex -shell-escape -output-directory bin *.tex
	biber --output_align ./bin/20131212-DatVid-G-Opg.3.bcf
	pdflatex -shell-escape -output-directory bin *.tex
	pdflatex -shell-escape -output-directory bin *.tex
	make clean
clean:
	rm -f ./bin/*.{aux,toc,blg,bbl,log,out,.run.xml}

