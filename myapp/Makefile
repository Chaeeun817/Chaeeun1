CC = gcc
OUTPUT = main
.SUFFIXES: .o .c
.PHONY: clean

$(OUTPUT): 
	$(CC) main.c -L/myproject/lib -lfuncs -o main

.c.o:
	$(CC) -c $< -o $@

clean:
	rm *.o $(OUTPUT)
