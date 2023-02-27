# dragino lora testing
# Single lora testing app

CC=g++
CFLAGS=-c -Wall
LIBS=-lwiringPi

all: run_program

run_program: main.o
	$(CC) main.o  $(LIBS) -o run_program

main.o: main.c
	$(CC) $(CFLAGS) main.c

clean:
	rm *.o run_program	
