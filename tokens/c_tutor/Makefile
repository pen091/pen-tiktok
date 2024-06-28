

cc = gcc
clag_obj = -c
clag_exec = -o

#target :  prerequisite
#	recipe

run : variable
	clear
	./variable


variable : variable.o
	$(cc) $(clag_exec) variable variable.o

variable.o : variable.c
	$(cc) $(clag_obj) variable.c

clean :
	sudo rm -rf *.o
	sudo rm -rf variable

