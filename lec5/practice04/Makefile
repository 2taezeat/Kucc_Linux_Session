TARGET = app.out
OBJS = main.o math.o print_functions.o
CC = gcc
CFLAGE = -g -Wall


all: $(TARGET)


main.o: main.c print_functions.h math.h
	$(CC) $(CFLAGE) -c main.c

math.o: math.c
	$(CC) $(CFLAGE) -c math.c

print_functions.o: print_functions.c
	$(CC) $(CFLAGE) -c print_functions.c

$(TARGET): $(OBJS)
	$(CC) $(CLFAGE) -o $@ $^

clean1: 
	rm *.o
	rm $(TARGET)
