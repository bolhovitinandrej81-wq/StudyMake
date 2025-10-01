# Переменные
TARGET = program
SRC  = main.c helper.c
OBJ  = main.c helper.o
CC    = gcc
CFLAGS  = -Wall

$(TARGET): $(OBJ)
	    $(CC) $(CFLAGS)  -o $(TARGET) $(OBJ)

main.o: main.c helper.h
        $(CC) $(CFLAGS) -c main.c
        
helper.o: helper.c helper.h
	    $(CC) $(CFLAGS) -c helper.c

clean:
	rm -f $(OBJ) $(TARGET)
	
.PHONY: clean

