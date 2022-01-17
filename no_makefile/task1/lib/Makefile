CC:=gcc
CFLAGS:=-Wall -shared
LIB:=libfile_reader.so
OBJ_FILE:=file_reader.o
SRC:=$(wildcard *.c)

all: $(LIB)

$(LIB):
	$(CC) -c -fPIC $(SRC)
	$(CC) $(CFLAGS) -o $(LIB) $(OBJ_FILE) $^
	rm -f $(OBJ_FILE)

clean:
	rm -f $(LIB)
