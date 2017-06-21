# Asteroids
## Game Design Document
Versão: 1.0

## Autores:
- Adham Lucas - adhamlucas20@gmail.com
- Edson Barros - edson.limajr@gmail.com
- Roberta Cruz - ro31cruz@gmail.com
- Tiago Aranha - tiagoweb@gmail.com
- Vitor Simões - vitor6427126@gmail.com
- Wesley Rocha - wesleysr1997@gmail.com

## História

O jogo em questão é um clone do jogo Asteroids. Este é um jogo de arcade com gráficos vetoriais muito popular lançado em 1979 pela Atari. O objetivo do jogo é destruir asteroides sem se deixar ser atingido por seus fragmentos. (Wikipédia)


## Gameplay
    1.O jogo possui uma missão muito simples: Navegar uma nave espacial em meio a asteriodes de 3 tamanhos, atirar mísseis nestes asterois e destrui-los completamente. 
    2.Cada tiro num asteroíde possui uma pontuação diferente. Um tiro num asteroide grande soma 20 pontos ao score, no asteroide mdio e pequeno, somam-se 100 pontos , nas patrulhas, somam-se 1000 pontos.
    3.Inicialmente o jogador possui 3 vidas, ou seja, pode ser atingido por um dos asteroides 3 vez antes de perde o jogo e obter seu numero final de scores. Ao alcançar a marca de 50mil pontos, o jogador ganha uma vida extra que  somada às que ele ja possui.
    4. A condição para "game over" é ser atingido o numero de vezes igual às vidas que possui. 
    5. O Jogo não posui avanço de fases, o cenario permanece inalterado por todo o jogo. A emoço principal do jogo  obter o maior numero de score. Pode ser jogado por várias pesoas e formar um ranking de scores. O jogo não possui a opço de pausa, o que torna a quebra de recoredes mais dificil. O jogo principal possui um recorde oficial de 41.338.740 pontos. O jogador ficou jogando por mais de 58 horas initeruptamente.
    

## Personagens

    1. Nave Espacial
    2. Patrulha (Disco voador) Maior
    3. Patrulha (Disco voador) Menor
    4. Asteroide Grande
    5. Asteroide Médio
    6. Asteroide Pequeno

## Controles
    
    1. Movimentação da nave no espaço: A nave pode ser controlada pelo acelarador (tecla UP) que direciona a nave para frente e aumenta a acelaração quando a tecla permance acionada e diminui a aceleração até parar quando a tecla deixa de ser pressionada. A nave também pode girar em seu próprio eixo com a utilização das teclas seta para direita e seta para esquerda, o que fará com que a nave, caso esteja em movimento tenha sua direção modificada de acordo com a telca pressionada (direita ou esqureda)

    2. Hyperespaço: A nave pode viajar para o hyperespaço e surgir instantaneamente em qualquer ponto do espaço ao ser acionada a tecla shift do lado esquerdo do teclado.

    3. A nave atira misseis caso a tecla barra de espaços seja acionada. Caso a tecla se mantenha acionada, a nave atira sequencialmente misseis até que a tecla deixe de ser pressionada.

## Câmera
   1. O jogo é mostrado em 2D, sendo o universo ao fundo e a nave vista de cima bem como os asteroides e as patrulhas. O jogo apresenta um efeito circular nas bordas, ou seja, quando a nave atravessa uma das bordas ela reaparece na borda paralela na mesma em direção que sumiu.
   
## Universo do Jogo
    1. O jogo se passa no espaço sideral. O jogo, tanto original, quanto este clone, não possui fases gradativas que alteram o cenário. A emoção principal do jogo é alcançar o maior score possível. O que torna o jogo mais difícil é o fato dele não ter a opção de pausar. Uma vez iniciado, o jogador precisa manter o mesmo jogo para alcaçar o recorde anterior. 
    2. No ambiente do jogo é possivel ouvir os sons dos propulsores da nave, dos disparos dos mísseis e da explosão dos asteriodes.
    
## Inimigos

    1. Patrulha (Disco voador) Maior
    2. Patrulha (Disco voador) Menor
    3. Asteroide Grande
    4. Asteroide Médio
    5. Asteroide Pequeno


## Interface
    1. Inicialmente o Menu onde é mostrado a opção "Play game" e "High Socre". A primeira incia o jogo que é descrito no item 2.       e a segunda mostra o máximo de pontos feitos pelos jogadores
    2. Fundo preto representando o espaço sideral. As estrelas representadas por pontos minúscolos sobre o fundo preto. No topo à esquerda a pontuação e logo abaixo a quantidade de vidas. As personagens serão desenhadas com figuras geométricas vetoriais.
