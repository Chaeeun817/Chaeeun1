CC = gcc
OBJFILES = func1.o func2.o
OUTPUT = libfuncs.a
.SUFFIXES: -o -c
.PHONY: clean


$(OUTPUT): $(OBJFILES)
	ar rv $(OUTPUT) $(OBJFILES)

.c.o:
	$(CC) -c -I../include $< -o $@

clean:
	rm *.o main
