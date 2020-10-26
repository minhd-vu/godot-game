PROJECT_NAME=godot-game

all: simple

simple: simple.c
	gcc -std=c11 -fPIC -c -I../godot_headers simple.c -o simple.o
	gcc -rdynamic -shared simple.o -o ../${PROJECT_NAME}/bin/libsimple.so