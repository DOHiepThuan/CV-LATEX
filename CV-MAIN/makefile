main="cv-dohiepthuan"
latex="pdflatex"
bibtex="bibtex"
journal = "REVUE"
inter="ACTI"
national="ACTN"

all: cleanAll compiler clean


compiler: 
	$(latex) $(main).tex
# 	$(bibtex) $(journal).aux
# 	$(bibtex) $(inter).aux
# 	$(bibtex) $(national).aux
	$(latex) $(main).tex
	$(latex) $(main).tex
	$(latex) $(main).tex

clean:
	rm -vf *.aux  *.*~ *.bbl *.blg *.log *.out  ./lib-tex/*~  ./bibtex/*~

cleanAll:
	rm -vf *.aux *.pdf *.*~ *.bbl *.blg *.log *.out  ./lib-tex/*~  ./bibtex/*~


	
