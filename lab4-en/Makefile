.PHONY: all pdf clean

all: clean pdf

pdf:
	latexmk -pdf -silent -time -pdflatex="pdflatex -interaction=nonstopmode -synctex=1" -use-make -aux-directory=build --output-directory=build main.tex

clean:
	rm -rf build
