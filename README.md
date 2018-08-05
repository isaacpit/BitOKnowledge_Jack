# BitOKnowledge_Jack
Game of conversion between different numerical bases. The game was implemented in the Jack programming language. This project was built to work with Noam Nisan and Shimon Schocken's nand2tetris architecture. 
By Isaac Pitblado


Classes used:
Random - Pseudo random number generator
	Credit: 
	"Random Number Generator
	Original author: Taylor Wacker
	Modified by: Connor McKay

	This is a pseudo random number generator that uses the
	Linear Congruential Generator (LCG) to generate random
	numbers."
BinaryGame - is the only class implemented with methods drawBorder(), run(), logic(), gameOver(), and generateBin() in order to control the game logic.

File Structure:
	    Random.jack 
	  / 
Main.jack 
	  \
	    BinaryGame.jack


Compile: 
	In order to compile the game, first navigate to the directory holding all of the .jackc files. Then just use the following command in the command prompt: 
	"JackCompiler.sh"
