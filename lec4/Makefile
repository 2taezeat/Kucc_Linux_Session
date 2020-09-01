SRCDIR = ./src/

main.o: ${SRCDIR}main.c
	gcc ${SRCDIR}main.c -c

print_functions.o: ${SRCDIR}print_functions.c
	gcc ${SRCDIR}print_functions.c -c

math.o: ${SRCDIR}math.c
	gcc ${SRCDIR}math.c -c



all: *.o
	gcc *.o -o nothing

