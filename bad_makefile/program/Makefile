CC:=gcc
CFLAGS:=-Wall -Ipwd
SRC:=$(wildcard *.c)
OBJS:=$(SRC:.c=.o)
BIN:=calculator
LDFLAGS:=-L ../library -lcalculator
CPPFLAGS:=-I ../library

.PHONY: all clean

all: $(BIN)

$(BIN): $(OBJS)
	$(CC) -o $@ $^ $(LDFLAGS)

%.o: %.c
	$(CC) $(CPPFLAGS) -c -o $@ $^

clean:
	$(RM) $(BIN) $(OBJS)
