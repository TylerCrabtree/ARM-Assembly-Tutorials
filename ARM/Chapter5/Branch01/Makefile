#Makefile

all: branch01

branch01: branch01.o
	gcc -o $@ $+

branch01.o : branch01.s
	as -o $@ $<

clean:
	rm -vf branch01 *.o
