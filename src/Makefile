All: tiles board clean

tiles:
	./latexdockercmd.sh pdflatex tableau_tiles_1.tex
	./latexdockercmd.sh pdflatex tableau_tiles_2.tex
	./latexdockercmd.sh pdflatex tableau_tiles_3.tex
	mv tableau_tiles_1.pdf ../
	mv tableau_tiles_2.pdf ../
	mv tableau_tiles_3.pdf ../

board:
	./latexdockercmd.sh pdflatex player_board.tex
	mv player_board.pdf ../
	
clean:
	rm *.log *.aux
