# FILES=$(patsubst %.*, %., main.tex)
# FILES += $(patsubst %.md, %.pdf, $(wildcard *.md))
all:
	pdflatex --shell-escape presentation.tex -interaction=scrollmode

draft:
	pdflatex --shell-escape presentation.tex -interaction=scrollmode -draftmode

print:
	ls main.*
