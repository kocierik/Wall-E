- Command-line compile.  In the mnkgame/ directory run::

		


MNKGame application:

- Human vs Computer.  In the mnkgame/ directory run:
	
		java -cp ".." mnkgame.MNKGame 3 3 3 mnkgame.S
		java -cp ".." mnkgame.MNKGame 4 3 3 mnkgame.S
		java -cp ".." mnkgame.MNKGame 4 4 3 mnkgame.S
		java -cp ".." mnkgame.MNKGame 4 4 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 5 5 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 5 5 5 mnkgame.S
		java -cp ".." mnkgame.MNKGame 6 4 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 6 5 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 6 6 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 6 6 5 mnkgame.S
		java -cp ".." mnkgame.MNKGame 6 6 6 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 4 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 5 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 6 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 7 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 5 5 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 6 5 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 7 5 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 7 6 mnkgame.S
		java -cp ".." mnkgame.MNKGame 7 7 7 mnkgame.S
		java -cp ".." mnkgame.MNKGame 8 8 4 mnkgame.S
		java -cp ".." mnkgame.MNKGame 10 10 5 mnkgame.S


- Computer vs Computer. In the mnkgame/ directory run:

		java -cp ".." mnkgame.MNKGame 3 3 3 mnkgame.S mnkgame.QuasiRandomPlayer


MNKPlayerTester application:

- Output score only:

	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.S mnkgame.QuasiRandomPlayer

- Output score repetitions:

		java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 4 3 3 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 4 4 3 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 4 4 4 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 5 4 4 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 5 5 4 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 5 5 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 6 4 4 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 6 5 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 6 6 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 6 6 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 6 6 6 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 4 4 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 5 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 7 6 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 7 7 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 7 5 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 6 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 7 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 7 6 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 7 7 7 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 8 8 4 mnkgame.S mnkgame.Solution -r 2 #win1
		java -cp ".." mnkgame.MNKPlayerTester 10 10 5 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 50 50 10 mnkgame.S mnkgame.Solution -r 2
		java -cp ".." mnkgame.MNKPlayerTester 70 70 10 mnkgame.S mnkgame.Solution -r 2

- Verbose output:

`	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.S mnkgame.QuasiRandomPlayer -v `


- Verbose output and customized timeout (1 sec) and number of game repetitions (10 rounds): 

DA PRIMO
```
	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 3 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 4 4 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 4 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 5 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 5 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 6 6 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 6 6 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 6 6 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 5 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 7 6 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 7 7 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1

	java -cp ".." mnkgame.MNKPlayerTester 7 5 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 6 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 6 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 7 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 8 8 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 #win1
	java -cp ".." mnkgame.MNKPlayerTester 10 10 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
```
	DA SECONDO
```
	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 3 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 5 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 5 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 6 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 6 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 6 6 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 5 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 6 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3

	java -cp ".." mnkgame.MNKPlayerTester 7 5 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 6 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 7 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 8 8 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 6 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 10 10 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3

	--------------------------------------------------------------------------------------------
```
	DA PRIMO
```
	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 3 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 3 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 5 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 5 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 5 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3 
	java -cp ".." mnkgame.MNKPlayerTester 6 6 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3	 
	java -cp ".." mnkgame.MNKPlayerTester 6 6 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3  
	java -cp ".." mnkgame.MNKPlayerTester 6 6 6 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 4 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 5 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 6 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 3

	java -cp ".." mnkgame.MNKPlayerTester 7 5 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2 
	java -cp ".." mnkgame.MNKPlayerTester 7 6 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 6 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 7 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 8 8 4 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 10 10 5 mnkgame.S mnkgame.QuasiRandomPlayer -v -t 1 -r 2
```
	DA SECONDO
```
	java -cp ".." mnkgame.MNKPlayerTester 3 3 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 3 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 3 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 4 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 5 5 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3  
	java -cp ".." mnkgame.MNKPlayerTester 5 5 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 5 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 6 6 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3 
	java -cp ".." mnkgame.MNKPlayerTester 6 6 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3 
	java -cp ".." mnkgame.MNKPlayerTester 6 6 6 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 4 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 5 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 6 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 7 7 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3

	java -cp ".." mnkgame.MNKPlayerTester 7 5 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 6 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 6 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 7 7 7 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 8 8 4 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 2
	java -cp ".." mnkgame.MNKPlayerTester 10 10 5 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 3
	java -cp ".." mnkgame.MNKPlayerTester 50 50 10 mnkgame.QuasiRandomPlayer mnkgame.S -v -t 1 -r 1
```
