main : figures podc-presentation.tex
	pdflatex podc-presentation.tex

figures : MSQueue CASretry OrderTree Blocks

MSQueue : MSQueue.fig
	./fig2layer 1 1 +48:50 MSQueue
	./fig2layer 1 2 +48:51 MSQueue
	./fig2layer 1 3 +48:52 MSQueue
	./fig2layer 1 4 +48,50:53 MSQueue
	./fig2layer 1 5 +50:54 MSQueue

CASretry : CASretry.fig
	./fig2layer 1 1 +49:50 CASretry
	./fig2layer 1 2 +49:51 CASretry
	./fig2layer 1 3 +49:52 CASretry

OrderTree : OrderTree.fig
	./fig2layer 0.8 1 +50 OrderTree
	./fig2layer 0.8 2 +50:51 OrderTree
	./fig2layer 0.8 3 +49:52 OrderTree
	./fig2layer 0.8 4 +48:53 OrderTree
	./fig2layer 0.6 5 +50:53 OrderTree
	./fig2layer 0.6 6 +48,50:53 OrderTree
	./fig2layer 0.6 7 +50:54 OrderTree
	./fig2layer 0.6 8 +50:55 OrderTree
	./fig2layer 0.6 9 +50:56 OrderTree
	./fig2layer 0.6 10 +47,50:53 OrderTree

Blocks : Blocks.fig
	./fig2layer 0.6 0 +1 Blocks
	./fig2layer 0.6 1 +50 Blocks
	./fig2layer 0.6 2 +49:50 Blocks
	./fig2layer 0.6 3 +45,47:51 Blocks
	./fig2layer 0.6 4 +45:51 Blocks
	./fig2layer 0.6 5 +45:46,48:50,52 Blocks
	./fig2layer 0.6 6 +45:46,48:51,53,54 Blocks
	./fig2layer 0.6 7 +45:46,48:51,53,55 Blocks
	./fig2layer 0.6 8 +45:46,48:51,53,56 Blocks
	./fig2layer 0.6 9 +45:46,48:51,57 Blocks
