# Arquitetura

*AS funções relacionadas ao gerenciamento das casa do jogo da velha ficaram no modulo  **jogodavelho.py**.

*O estado de cada casa do jogo será representada por uma string: "." para cada vazia; "X" para casa ocupada pelo primeiro jogador; "O" para casa ocupada pelo segundo jogador

*A função inicializar () retornará uma lista tx3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.