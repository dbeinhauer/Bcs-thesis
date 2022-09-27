EXT?=md


SRC=$(wildcard *.$(EXT))
TEX=$(SRC:.$(EXT)=.tex)

OPTS=-f markdown -t latex
PANDOCMAKE=pandoc $(OPTS)


all: $(TEX) 


clean:
	rm -f $(TEX)

%.tex: %.md
	$(PANDOCMAKE)  -o $@ $<

