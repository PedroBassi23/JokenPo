# JoKenPo
Será que uma Rede Neural consegue prever sua próxima jogada em um jogo de pedra, papel e tesoura?


Jogue aqui

Jogue aqui [here](https://pedrobassi23.github.io/JokenPo/)
Jogue aqui [[here](https://victorribeiro.com/jokenpo)]
![jokenpo (2)](https://github.com/user-attachments/assets/58ddf297-8001-46a5-8a6f-9917fb5dfd13)


# Sobre
Este é um experimento envolvendo o clássico jogo Pedra, Papel e Tesoura, também conhecido como Jo Ken Po. Durante as três primeiras rodadas, o computador escolhe um movimento (pedra, papel ou tesoura) de forma aleatória. A partir da quarta rodada, ele assume que já tem dados suficientes sobre o jogador para tentar prever seu padrão de jogadas.

O conjunto de dados utilizado para essa previsão consiste nos dois últimos movimentos do jogador. O primeiro movimento é armazenado como entrada (x), e o segundo como rótulo ou alvo (y). Ou seja, se o jogador escolhe pedra em uma rodada e depois joga papel, o sistema aprende que, após jogar pedra, há uma chance de o jogador escolher papel na próxima rodada.

Se a rede neural prevê que o jogador jogará pedra, por exemplo, o computador joga papel para vencer a rodada. Caso o computador perca, ele treina a rede neural novamente com os novos dados coletados.

# Problemas conhecidos
Este é apenas um experimento, então não se frustre se a rede neural não jogar muito bem contra você. Além disso, os dados nunca são apagados do conjunto de treinamento, o que significa que, com o tempo, o processo de treinamento pode ficar mais demorado.
