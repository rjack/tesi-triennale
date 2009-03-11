JUNK=tesi.aux tesi.log tesi.toc
OUTPUT=tesi.pdf

all	: $(OUTPUT)

%.pdf	: %.tex
	for i in `seq 1 3` ; do pdflatex $< ; done

clean	:
	rm -f $(JUNK) $(OUTPUT)
