all:
	../rc.native test.expr 
	./test
	gcc -m32 -g ../runtime/runtime.c test.s -o test
	cat test.input |../rc.native -i test.expr
