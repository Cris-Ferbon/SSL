CC = clang
CFLAGS = -Wall -Wextra -g -std=c23 -pedantic-errors 
TARGET = hello.exe
SRC = hello.c

all: $(TARGET) run

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

run: $(TARGET)
	./$(TARGET) > output.txt

clean:
	rm -f $(TARGET)

