calculoII.pdf: calculoII.tex ./Temas/* mrproper
	pdflatex -shell-escape -interaction=nonstopmode -file-line-error calculoII.tex
	make mrproper
	pdflatex -shell-escape -interaction=nonstopmode -file-line-error calculoII.tex
	make mrproper



mrproper:
	find . -regex ".*~" -exec rm -r {} \; # Borra ficheros temporales recursivamente
	rm -f *.aux
	rm -f *.log
	rm -f *.nav
	rm -f *.out
	rm -f *.vrb
	rm -f *.snm
	rm -f *.toc
	rm -f *.synctex.gz
