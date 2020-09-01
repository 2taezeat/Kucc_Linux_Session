
app.out: main.o math.o print_functions.o
	gcc -o app.out main.o math.o print_functions.o


main.o: main.c print_functions.h math.h
	gcc -c main.c

math.o: math.c
	gcc -c math.c

print_functions.o: print_functions.c
	gcc -c print_functions.c

clean1: 
	rm *.o
	rm app.out
