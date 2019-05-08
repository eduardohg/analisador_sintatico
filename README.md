# analisador_sintatico
Trabalho da Disciplina de Compiladores - Desenvolver um Analisador Sintático

Análise Sintática para 27/06/19

Implementar um Analisador Sintático Descendente que:
- tome como entrada a lista proveniente do analisador léxico desenvolvido na 1a Fase
- efetue a análise sintática da sequência de tokens como mostrados nos Anexos 1 e 2 do Kowaltowski (1983) e capítulo 5;
- construa uma representação intermediária do programa fonte (árvore de programa) na forma de árvore n-ária (árvore abstrata que será dada em aula);
- monte a tabela de símbolos utilizando da função hash sugerida em Aho (1986) acrescentando novos atributos do Kowaltowski (1983) da página 164 dados em aula.
Assim, o resultado da análise sintática será uma árvore n-ária que representa um programa sintaticamente correto junto com a tabela de símbolos.
