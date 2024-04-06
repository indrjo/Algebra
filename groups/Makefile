
.PHONY: clean

.RECIPEPREFIX = >

groups.pdf: groups.tex \
	    $(wildcard includes/*.tex) \
	    ../structure.tex \
	    ../macros.tex
> @latexmk -lualatex groups.tex 

#clean:
#> latexmk -c

