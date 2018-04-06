#Makefile

all: load01

load01: load01.o
	gcc -o $@ $+

load01.o : load01.s
	as -o $@ $<

clean:
	rm -vf load01 *.o
