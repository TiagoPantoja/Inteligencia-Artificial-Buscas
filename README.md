# Projeto Jogo da Velha com Algoritmo Minimax

Este é um simples jogo da velha em Python que permite que um jogador jogue contra um agente de inteligência artificial baseado no algoritmo Minimax. O jogo é implementado no console e segue as regras tradicionais do jogo da velha.

## Funcionalidades

- Jogue contra um agente de IA ou outro jogador humano.
- Escolha o tamanho do tabuleiro (entre 3x3 e 5x5).
- Desfrute da lógica de IA baseada no algoritmo Minimax para uma experiência desafiadora.
- Veja o resultado do jogo no console.

## Algoritmo Minimax

O algoritmo Minimax é uma técnica de tomada de decisão em jogos com dois jogadores, onde um jogador busca minimizar a perda máxima possível e o outro busca maximizar o ganho mínimo possível. No contexto do Jogo da Velha, o algoritmo Minimax é usado pela IA para analisar todas as jogadas possíveis e escolher a jogada que maximiza suas chances de vencer ou minimiza suas chances de perder.

O algoritmo funciona em profundidade, explorando todas as jogadas possíveis em um espaço de busca, criando uma árvore de possibilidades. Ele atribui valores a cada nó da árvore com base na avaliação do estado do jogo. O agente escolhe o caminho que leva ao resultado mais favorável para ele. No Jogo da Velha, o agente busca maximizar suas chances de ganhar e minimizar as chances do jogador humano ganhar.

## Como Jogar

1. Execute o arquivo `jogo_da_velha.py`.
2. Escolha o tamanho do tabuleiro e quem vai começar (usuário ou agente).
3. Siga as instruções no console para fazer suas jogadas.
4. O jogo terminará quando um jogador vencer ou ocorrer um empate.

## Exemplo de Uso
`python jogo_da_velha.py`

# Projeto Labirinto Solucionador com Busca em Largura

Este projeto em Python é um solucionador de labirinto usando o algoritmo de Busca em Largura (BFS). Ele recebe um mapa de labirinto como entrada e encontra o caminho mais curto do ponto de partida ao ponto de destino.

## Funcionalidades

- Leitura de um mapa de labirinto a partir de uma matriz.
- Solução do labirinto usando o algoritmo BFS.
- Visualização do caminho no mapa de labirinto.
- Exibição do custo total do caminho.

## Busca em Largura (BFS)

A Busca em Largura (BFS) é um algoritmo de busca que explora todos os vértices vizinhos antes de seguir para os próximos níveis de vizinhança. No contexto do solucionador de labirinto, o algoritmo BFS é usado para encontrar o caminho mais curto do ponto de partida ao ponto de destino, garantindo que o caminho encontrado seja o mais curto possível.

O algoritmo BFS começa no ponto de partida, visita todos os vizinhos desse ponto, depois visita todos os vizinhos dos vizinhos, e assim por diante, até encontrar o ponto de destino. Ele mantém uma fila para rastrear os próximos pontos a serem visitados, garantindo que os caminhos mais curtos sejam explorados primeiro.

## Como Usar

1. Execute o arquivo `labirinto_solucionador.py`.
2. O programa encontrará o caminho mais curto no labirinto.
3. O caminho e o custo total serão exibidos no console.

## Exemplo de Uso
`python labirinto_solucionador.py`
