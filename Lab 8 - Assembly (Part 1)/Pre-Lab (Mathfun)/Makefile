#Nathaniel Goldammer (wsn8pk) - March 29th, 2022 - Makefile

CXX = clang++
CXXFLAGS = -Wall -g
AS = nasm
ASFLAGS = -f elf64 -g
OBJECTS = mathlib.o mathfun.o 

a.out: $(OBJECTS)
	$(CXX) $(CXXFLAGS) $(OBJECTS)

clean:
	-rm -f *.o *~