CC=gcc
CFLAGS=-O3 -ffast-math
LIBS=-lSDL -lSDL_mixer -s -lm

just4qix: main.o render.o update.o input.o sound.o particle.o
	$(CC) main.o render.o update.o input.o sound.o particle.o -o just4qix $(LIBS)

clean:
	-rm -rf *.o
	-rm -rf just4qix
