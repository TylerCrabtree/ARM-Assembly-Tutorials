#Makefile

all: loop01

branch01: loop01.o
	gcc -o $@ $+

loop01.o : loop01.s
	as -o $@ $<

clean:
	rm -vf loop01 *.o
