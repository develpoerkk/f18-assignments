TEX := pdflatex
FLAGS := -shell-escape

all: assign1.pdf

%.pdf: %.tex
	${TEX} ${FLAGS} $^

check:
	aspell -t -c *.tex

clean:
	rm -rf *.aux *.log *.out *.pdf _minted-*
