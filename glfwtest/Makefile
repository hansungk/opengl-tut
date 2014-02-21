# Compiler to use
CC=g++
# CFLAGS to be passed to the compiler
CFLAGS=-g -Wall
# Include path
INCLUDE=
# Libraries to be linked to
# Ex: libGLEW.so -> -lGLEW
# Mac OS X needs -framework flags as well
LIBS=-lGLEW -lglfw -framework OpenGL
# Project name, coincides with the executable name
PROJECT=glfwtest

all: $(PROJECT)

$(PROJECT): $(PROJECT).cpp
	$(CC) $(PROJECT).cpp $(CFLAGS) -o $(PROJECT) $(LIBS)

clean:
	rm -rf *.o $(PROJECT) *dSYM
