JUNK=tesi.aux tesi.log tesi.toc
OUTPUT=tesi.pdf

all	: $(OUTPUT)

%.pdf	: %.tex
	pdflatex $<

clean	:
	rm -f $(JUNK) $(OUTPUT)
