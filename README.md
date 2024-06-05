# Relatório Explicativo
## Modelagem do Jogo
### Tela e Objetos
O jogo é projetado para ser exibido em uma tela de 800x600 pixels. Ele inclui dois jogadores, representados por retângulos, e uma bola representada por uma elipse.

### Velocidades
A velocidade dos jogadores é fixada em 20 pixels por movimento. A bola começa com uma velocidade de 5 pixels tanto no eixo X quanto no eixo Y, aumentando a cada colisão com um jogador.

## Controle do Jogo
### Movimentação
Os jogadores da esquerda e da direita são controlados pelas teclas W/S e O/L, respectivamente.

### Pausar e Retomar
O jogo pode ser pausado e retomado pressionando a tecla P.

## Funções do Código
* draw_field() - Esta função desenha o campo de jogo, incluindo os jogadores, a bola e a linha central.

* update_ball() - Esta função atualiza a posição da bola, verifica colisões com os jogadores e as paredes, e detecta pontuações.

* reset_ball() - Esta função reseta a posição da bola e a velocidade após um ponto ser marcado.

* draw_score() - Esta função desenha o placar na tela.

* main() - Esta função contém o loop principal do jogo, processa eventos, atualiza estados e redesenha a tela a cada frame.

## Controles
Jogador da Esquerda: W (para cima), S (para baixo)

Jogador da Direita: O (para cima), L (para baixo)

Pausar/Despausar: P

Com esses controles e lógica, o jogo permite uma experiência de Pong clássica
