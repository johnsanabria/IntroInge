INPUT="presentacion-historia_computacion"
2pdf:
	pandoc -t beamer -V colorlinks --slide-level=2 --toc $(INPUT).md -o $(INPUT).pdf

s5:
	pandoc -t s5 -s $(INPUT).md -o $(INPUT).html

slidy:
	pandoc -t slidy -s $(INPUT).md -o $(INPUT).html

slideous:
	pandoc -t slideous -s $(INPUT).md -o $(INPUT).html

dzslides:
	pandoc -t dzslides -s $(INPUT).md -o $(INPUT).html

revealjs:
	pandoc -t revealjs -s $(INPUT).md -o $(INPUT).html
