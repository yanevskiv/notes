TARGET = kdp-skripta.pdf
MAINSRC = kdp-skripta.tex
SOURCES = $(wildcard sections/*.tex)
TEXCC = lualatex


$(TARGET): $(MAINSRC) $(SOURCES)
	$(TEXCC) $< $(MAINSRC)

clean:
	rm -f *.aux 
	rm -f *.pdf
	rm -f *.log
	rm -f *.toc
	rm -f *.out

.PHONY: clean
