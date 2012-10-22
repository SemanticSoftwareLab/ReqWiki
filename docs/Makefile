DOC=reqwiki_manual
LATEX=pdflatex
BIBTEX=bibtex
TEXIDATE=TeXidate
GRAPHICSDIR=graphics

all: guide

guide:  $(DOC).tex $(DOC).bib
	$(LATEX) $(DOC).tex
	$(BIBTEX) $(DOC)
	$(LATEX) $(DOC).tex
	$(LATEX) $(DOC).tex

clean:
	  rm -f *.aux	*.bbl	*.blg	*.log	*.pdf

reallyclean:
	rm *~ *.backup 