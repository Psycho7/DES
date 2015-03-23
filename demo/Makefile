CC = g++
FLAGS = -std=c++11
SRCDIR = ../src
OBJ = ../src/DES.o

all:  test

test: test.cpp $(OBJ) 
	$(CC) $(FLAGS) -o test $(OBJ) test.cpp

$(OBJ): $(SRCDIR)/DES.h $(SRCDIR)/DES.cpp
	cd $(SRCDIR) && $(CC) $(FLAGS) -c DES.h DES.cpp
