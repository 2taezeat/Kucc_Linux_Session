TARGET = app.out
OBJS = main.o math.o print_functions.o


$(TARGET): $(OBJS)
	gcc -o $(TARGET) $(OBJS)


main.o: main.c print_functions.h math.h
	gcc -c main.c

math.o: math.c
	gcc -c math.c

print_functions.o: print_functions.c
	gcc -c print_functions.c

clean1: 
	rm *.o
	rm $(TARGET)
