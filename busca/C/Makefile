CC = gcc
CFLAGS = -std=c99 -O2
OBJECTS = busca.o linearSearch.o

all: busca

busca: $(OBJECTS)
	gcc -o busca busca.o linearSearch.o

busca.o: busca.c
	gcc $(CFLAGS) busca.c -o busca.o -c

linearSearch.o: linearSearch.c
	gcc $(CFLAGS) linearSearch.c -o linearSearch.o -c

clean:
	rm -f busca $(OBJECTS)
