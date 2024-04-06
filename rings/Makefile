
.PHONY: clean

.RECIPEPREFIX = >

DEPENDS = $(shell find . -type f -name '*.tex' -or -name '*.bib')

rings.pdf: $(DEPENDS) ../*.tex
> @latexmk -lualatex -lualatex='lualatex --synctex=1 %O %S' rings.tex 

#clean:
#> latexmk -c

