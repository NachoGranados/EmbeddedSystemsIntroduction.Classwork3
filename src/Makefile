build:
	cd ..
	export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$(PWD)/lib
	gcc -I../include calculadora.c -o ../bin/calculadora_e -L ../lib/ -l:liboperaciones.a -lm
	gcc -I../include calculadora.c -o ../bin/calculadora_d -L ../lib/ -loperaciones -lm