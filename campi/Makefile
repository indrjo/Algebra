.PHONY: clean

.RECIPEPREFIX = >

campi.pdf: campi.tex \
           preambolo.tex \
           biblio.bib
> @latexmk -lualatex $<

clean:
#> @latexmk -c
#> @rm *.bbl
#> @rm *.synctex.gz*
