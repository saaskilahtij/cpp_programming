dog_program : dog.o main.cpp
	g++ dog.o main.cpp -o dog_program

dog.o : dog.cpp dog.hpp
	g++ -c dog.cpp

clean : 
	rm dog_program *.o
