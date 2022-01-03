# JogoDeXadrez-Estudo

Não vale usar programação de jogas ja conhecidas de xadrez.

Tudo começa em uma matriz a1-h8.
Os objetos são as peças(genericas), e seus movimentos serão dinamicos, atribundo na propriedade movimentos. Sendo entao o objeto identificado pelo seus movimentos.
Dentro desse objeto, alem dos movimentos, tem as peculiaridades e regras, como o piao chegar no fim, e a troca da torre pelo rei, por exemplo.

Dai entao, sai a analise de peça/objeto a peça em tempo real, como primeira regra.
A segunda regra, é utilizar inteligencia artificial, pra ir gravando os condicionamentos do oponente.

Uma variavel de porcentagem de indice de ganhando/perdendo devera ser adicionada.


Sera dividido em camas de arquitetura de software:
Camada do tabuleiro;
Camada das peças;
Camada da porcentagem e analise da melhor decisao;
Camada do processamento das jogadas;

Se for o caso, depois de tudo desenvolvido, bater se a decisão coincide com as jogadas ja conhecidas do xadrez. Daqui poderá sair testes unitarios TDDs.

Camadas tecnicas, como BD/APIs/ThredCalcCore/IA(K-means).

E por ultimo a camada de interface.
