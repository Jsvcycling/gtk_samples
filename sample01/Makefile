NAME=sample01

CC=gcc
CCFLAGS=-Wall `pkg-config --cflags gtk+-3.0`
LDFLAGS=`pkg-config --libs gtk+-3.0`

all:
	$(CC) $(CCFLAGS) $(NAME).c -o ../bin/$(NAME) $(LDFLAGS)

clean:
	rm ../bin/$(NAME)
