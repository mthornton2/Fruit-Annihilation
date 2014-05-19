CFLAGS = -I ./include
LFLAGS =  -lrt -lX11 -lGLU -lGL -pthread -lm #-lXrandr

all: lab2_rainforest

lab2_rainforest: final.c ppm.c log.c
	gcc $(CFLAGS) final.c ppm.c log.c  -Wall -Wextra $(LFLAGS) -o final

clean:
	rm -f lab2_rainforest
	rm -f *.o

