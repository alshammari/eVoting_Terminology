all:	 voteVerif.tex;
	 pdflatex   voteVerif;
	 bibtex  voteVerif;
	 pdflatex   voteVerif;
	 pdflatex   voteVerif;

cl:
	rm -f *.log; 
	rm -f *.aux ;
	rm -f *.dvi; rm -f *.toc;
	rm -f  *.bbl; rm -f *.idx; rm -f *.ilg
	rm -f  *.blg; rm -f *~; rm -f *.ind
	rm -f ; rm -f *.dvi;
view:	all
	open voteVerif.pdf 
vcl:  cl
	rm -f *.pdf; rm -rf *.gz; rm -f *.ps; rm -f 
