#Makefile

all: store01

store01: store01.o
	gcc -o $@ $+

store01.o : store01.s
	as -o $@ $<

clean:
	rm -vf store01 *.o
