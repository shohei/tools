# Project: ujprog
# Makefile created by Dev-C++ 4.9.9.2

CPP  = g++.exe
CC   = gcc.exe
WINDRES = windres.exe
RES  = 
OBJ  = ujprog.o $(RES)
LINKOBJ  = ujprog.o $(RES)
#LIBS =  -s -static -L"C:/Dev-Cpp/MinGW64/lib" -L. -lftd2xx  
LIBS =  -s -static -L"C:/Dev-Cpp/MinGW64/lib" -L. -lftd2xx  
INCS =  -Wno-traditional -I"C:/Dev-Cpp/MinGW64/include"  -I.
CXXINCS =  -I"C:/Dev-Cpp/MinGW64/lib/gcc/x86_64-w64-mingw32/4.9.2/include"  -I"C:/Dev-Cpp/MinGW64/include"  -I.
BIN  = ujprog.exe
CXXFLAGS = $(CXXINCS)  
CFLAGS = $(INCS)  
RM = rm -f

.PHONY: all all-before all-after clean clean-custom

all: all-before ujprog.exe all-after


clean: clean-custom
	${RM} $(OBJ) $(BIN)

$(BIN): $(OBJ)
	$(CC) $(LINKOBJ) -lftd2xx -o "ujprog.exe" $(LIBS)

ujprog.o: ujprog.c
	$(CC) -c ujprog.c -o ujprog.o $(CFLAGS)
