# Campo Minado em Java
    Este é um Campo Minado feito em Java com alguns testes feitos em Junit.

## Regras do Jogo
    O objetivo do jogo é descobrir todos os quadrados que não contêm minas sem detonar nenhuma mina. O jogo começa com um tabuleiro de quadrados não revelados, em que algumas dessas células contêm minas.

    O jogador pode revelar um quadrado ou marca-lo ao digitar as coodernadas no padrão "x, y". Se a célula selecionada contiver uma mina, o jogo acabará e o jogador perderá. Se a célula não contiver uma mina, um número aparecerá na célula indicando quantas minas estão presentes nas seis células vizinhas. Usando essa informação, o jogador pode deduzir quais células são seguras. O jogador pode marcar uma célula como contendo uma mina clicando selecionando a opção "(des)marcar" ao digita uma coodernada.

    O jogo é ganho quando o jogador revela todas as células que não contêm minas.

    
## Como jogar?

    Para jogar, basta baixar ou clonar este repositório em sua máquina local e executar o arquivo "Aplicacao.java" na sua IDE presente na pasta "cm" dentro da "src". O jogo iniciará automaticamente. O jogador pode digitar as coodernadas que deseja e escolher se deseja "abrir" ou "(Des)marcar". As coodernadas são digitas no padrão: "x,y".

    
## Como foi desenvolvido

    Este jogo foi desenvolvido usando a linguagem de programação Java e o framework Junit foi utilizado para fazer alguns testes. O Visual Studio Code foi utilizado para o desenvolvimento do código.

    O código-fonte está organizado em pacotes e inclui classes para representar o tabuleiro do jogo, a lógica do jogo e a interface gráfica do usuário.

## Conclusão 
    
    O Campo Minado é um jogo clássico que pode ser uma boa maneira de aprender programação Java e o framework Junit. Este projeto oferece uma implementação completa do jogo em formato de texto.