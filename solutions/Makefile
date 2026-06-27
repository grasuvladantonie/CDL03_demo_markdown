CFLAGS = -Wall -Wextra

check:
	cpplint hellocworld.c

test: helloworld
	./test.sh

all: helloworld

helloworld: helloworld.c

clean:
	-rm -f helloworld
	-rm -f *~
