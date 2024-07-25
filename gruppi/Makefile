.PHONY: clean

.RECIPEPREFIX = >

gruppi.pdf: gruppi.tex \
            preambolo.tex \
            biblio.bib \
	    $(wildcard sezioni/*.tex)
> @latexmk -lualatex $<

clean:
#> @latexmk -c
#> @rm *.bbl
#> @rm *.synctex.gz*
