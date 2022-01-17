CC:=gcc
BIN:=main
LDFLAGS:=-L ../lib -lfile_reader
SRC:=$(wildcard *.c)

.PHONY: all clean

all: $(BIN)

$(BIN): $(SRC)
	$(CC) $^ -o $@ $(LDFLAGS)


clean:
	$(RM) $(LIB)
