PROG = array01.exe 
SRC = array01.cpp
CFLAGS = -O2 -std=c++17
LIBS = 
CC = g++

all: $(PROG)

$(PROG): $(SRC)
	$(CC) -o $@ $(CFLAGS) $(SRC) $(LIBS)

clean:
ifeq ($(OS),Windows_NT)
	del $(PROG)
else
    rm -f $(PROG)
endif

.PHONY: all clean