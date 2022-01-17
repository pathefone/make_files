CC:=gcc
CFLAGS:=-o
LIB_DIR:=../lib
SRC_FILES:= $(LIB_DIR)/maths.c $(LIB_DIR)/usage.c main.c
BIN:=main

all: $(BIN)

$(BIN):
	$(CC) $(SRC_FILES) $(CFLAGS) $@

clean:
	$(RM) $(BIN)
