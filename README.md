# analisadorSintatico

## Instalação:

Ferramenta FLEX (Analisador Lexico) ????
`$ sudo apt-get install flex`
Ferramenta GCC (Compilador C)
`$ sudo apt-get install build-essentials`

Ferramenta YACC (Analisador Sintatico)
`$ sudo apt-get install bison`

## Compilação/execução do programa:


ou manualmente com os seguintes comandos:

`$ lex file.l`

`$ yacc file.y`

`$ gcc lex.yy.c y.tab.h -ll`

