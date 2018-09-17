srcdir  = .

main = hw2_response
figs = $(wildcard figs/*)

pdf : $(main).pdf
.PHONY: pdf

%.pdf: %.tex $(figs)
	texfot lualatex -shell-escape $(main).tex

clean :
	rm -rf *.pdf *.aux *.out *.log _minted*
