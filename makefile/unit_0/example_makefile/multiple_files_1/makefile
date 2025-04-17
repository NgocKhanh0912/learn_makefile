PROJECT_NAME = main

SRC = $(wildcard *.c)
OBJ = $(SRC:%.c=%.o)
EXE = $(PROJECT_NAME)

build: main.o print.o
	gcc main.o print.o -o main

main.o:
	gcc -c main.c -o main.o

print.o:
	gcc -c print.c -o print.o

clean:
	rm *.o *.exe
