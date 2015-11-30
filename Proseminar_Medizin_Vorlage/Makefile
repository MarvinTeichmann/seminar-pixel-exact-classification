SOURCE = vorlage

make:
	pdflatex $(SOURCE).tex -output-format=pdf # Referenzen erstellen
	makeglossaries $(SOURCE)
	bibtex $(SOURCE)
	pdflatex $(SOURCE).tex -output-format=pdf # Referenzen einbinden
	pdflatex $(SOURCE).tex -output-format=pdf # Referenzen einbinden
	make clean

ebook:
	latexml --dest=$(SOURCE).xml $(SOURCE).tex
	latexmlpost -dest=$(SOURCE).html $(SOURCE).xml
	ebook-convert $(SOURCE).html $(SOURCE).epub --language de --no-default-epub-cover

clean:
	rm -rf  $(TARGET) *.class *.html *.aux *.out *.thm *.idx *.toc *.ilg *.glg *.glo *.ist *.xdy *.fdb_latexmk *.bak *.blg *.glsdefs *.acn *.acr *.alg *.nls *.nlo *.bak *.pyg *.lot *.lof
	# rm -rf *.bbl *.ind *.gls # Needed for arxiv
