# Algoritmo CYK
Implementação do algoritmo de análise Cocke-Younger-Kasami em JavaScript
O algoritmo CYK (Cocke-Younger-Kasami) é um algoritmo utilizado para análise sintática de linguagens livres de contexto. Ele foi desenvolvido por John Cocke, Daniel Younger e Tadao Kasami em 1970. O algoritmo CYK é amplamente utilizado em processadores de linguagens, compiladores e outras aplicações que envolvem análise gramatical. A ideia central do algoritmo CYK é a construção de uma tabela de análise bottom-up (de baixo para cima), onde cada célula representa uma variável da gramática que gera uma determinada subpalavra da sentença de entrada. Essa tabela é preenchida de forma dinâmica, considerando todas as combinações possíveis de variáveis que geram as subpalavras da sentença.

## Objetivo

Desenvolver um programa para processamento de Gramáticas Livres do Contexto (GLCs). Dada a especificação de uma GLC *G* na Forma Normal de Chomsky e uma cadeia *w* ∈ Σ∗, seu programa deve determinar se *G* gera *w*, e devolver a matriz *Tabela* (vide descrição do algoritmo) e o status (aceita / rejeita). Em outras palavras, o problema é decidir se *w*  pertence a *L(G)*.



