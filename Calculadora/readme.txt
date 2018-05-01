O programa foi compilado e executado no SO Ubuntu Linux vers�es 16.04 e 17.10.

As vers�es do compilador utilizadas foram:
	gcc (Ubuntu 5.4.0-6ubuntu1) 5.4.0
	gcc (Ubuntu 7.2.0-8ubuntu3) 7.2.0

As bibliotecas utilizadas foram:
	Bibliotecas padr�o:
	stdio.h - cont�m as fun��es padr�o de entrada e sa�da
	stdlib.h - cont�m as fun��es necess�rias utilizadas para aloca��o din�mica de mem�ria

	Bibliotecas criadas pelo programador:
	stdtask.h - cont�m as declara��es das fun��es implementadas nos arquivos "stack.c" "expression.c" e "calculator.c"

Instru��es de compila��o:
	Primeiro os arquivos "stack.c" "expression.c" e "calculator.c" devem ser compilados com o par�metro -c afim de 
	gerar os arquivos objetos necess�rios para compila��o do arquivo "main.c".

	Sendo assim os arquivos devem ser compilados via terminal da seguinte forma:

	1. gcc -c stack.c		(gerando o arquivo stack.o)
	2. gcc -c expression.c		(gerando o arquivo expression.o)
	3. gcc -c calculator.c		(gerando o arquivo calculator.o)
	4. gcc -o main main.c stack.o expression.o calculator.o		(gerando o arquivo main)

	Ap�s isso o arquivo "main" deve ser executado via terminal da seguinte forma:

	./main