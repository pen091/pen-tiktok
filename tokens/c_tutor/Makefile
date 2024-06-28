
cc = gcc
clag_exec = -o
clag_obj = -c

#target : prerequisite
#	recipe

run : variable        				 # prerequisite
	clear 	      				 # recipe
	./variable    				 # recipe

variable : variable.o  				 # prerequisite
	$(cc) $(clag_exec) variable variable.o   # recipe 

variable.o : variable.c				 # prerequisite
	$(cc) $(clag_obj) variable.c		 # recipe

clean :						 # no prerequisite
	sudo rm -rf *.o				 # recipe
	sudo rm -rf variable			 # recipe
