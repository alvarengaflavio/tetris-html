# Tetris
Um jogo simples de Tetris contido em um arquivo `html`.

## Como jogar:

- Para iniciar o jogo basta abrir o arquivo <code>index.html</code> no seu navegador preferido.

### Controles:
- Setas para esquerda e direita: Movem a peça para os lados.  
- Seta para baixo: Acelera a queda da peça.  
- Seta para cima: Gira a peça.  


## Como funciona:

1. Estrutura do Jogo: O jogo é representado por uma grade de 10x20 células. Cada célula pode estar vazia ou preenchida com uma cor correspondente a uma peça.
2. Peças: As peças são definidas como matrizes de 0s e 1s, onde 1 representa uma parte da peça. Cada peça tem uma cor associada.
3. Movimentação: As peças caem automaticamente e podem ser movidas para a esquerda, direita e para baixo usando as setas do teclado. A seta para cima gira a peça.
4. Colisão: O jogo verifica colisões para evitar que as peças se sobreponham ou saiam da grade.
5. Pontuação: Quando uma linha é completamente preenchida, ela é removida e o jogador ganha pontos.
