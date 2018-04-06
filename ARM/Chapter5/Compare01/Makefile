#Makefile

all: compare01

compare01: compare01.o
	gcc -o $@ $+

compare01.o : compare01.s
	as -o $@ $<

clean:
	rm -vf compare01 *.o
