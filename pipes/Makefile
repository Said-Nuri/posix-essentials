SOURCE = nampipes.c pipes.c
EXE = nampipes pipes
CFLAGS = -Wall 
LIBS = 
OBJS = nampipes.o pipes.o
CC = gcc

all: $(EXE)

nampipes: nampipes.o
	$(CC) nampipes.o -o nampipes $(LIBS)

pipes: pipes.o
	$(CC) pipes.o -o pipes $(LIBS)

nampipes.o: nampipes.c
	$(CC) $(CFLAGS) -c nampipes.c

pipes.o: pipes.c
	$(CC) $(CFLAGS) -c pipes.c

clean:
	rm -f *.o $(EXE)
