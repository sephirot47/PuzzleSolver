all: main 

main: Image.o Piece.o main.cpp
	g++ -g -std=c++11 -o puzzlesolver main.cpp Image.o Piece.o -lsfml-graphics -lsfml-window -lsfml-system

Image.o: Image.h Image.cpp 
	g++ -g -std=c++11 -c Image.cpp -o Image.o 

Piece.o: Piece.h Piece.cpp 
	g++ -g -std=c++11 -c Piece.cpp -o Piece.o 

clean:
	rm *.o puzzlesolver

