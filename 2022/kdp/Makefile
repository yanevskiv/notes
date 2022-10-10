TARGET = kol_main.pdf
MAINSRC = kol_main.tex
SOURCES = $(wildcard kol_sections/*.tex)
TEXCC = lualatex


$(TARGET): $(MAINSRC) $(SOURCES)
	$(TEXCC) $< $(MAINSRC)

clean:
	rm -f *.aux 
	rm -f *.pdf
	rm -f *.log
	rm -f *.toc

.PHONY: clean

