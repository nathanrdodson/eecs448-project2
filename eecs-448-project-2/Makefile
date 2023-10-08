Battleship: main.o UserInteraction.o Board.o Ship.o
	g++ -std=c++11 -g -Wall main.o UserInteraction.o Board.o Ship.o -o Battleship

main.o: main.cpp UserInteraction.h Board.h Ship.h
	g++ -std=c++11 -g -Wall -c main.cpp

UserInteraction.o: UserInteraction.h UserInteraction.cpp
	g++ -std=c++11 -g -Wall -c UserInteraction.cpp

Board.o: Board.h Board.cpp
	g++ -std=c++11 -g -Wall -c Board.cpp

Ship.o: Ship.h Ship.cpp
	g++ -std=c++11 -g -Wall -c Ship.cpp

clean:
	rm *.o Battleship
