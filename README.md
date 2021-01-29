# Insurance-Claims-Simulation

Simulação do Seguro Agregado(perspectiva individual) feita em python de uma carteira fictícia gerada a partir de variáveis aleatórias.
Distribuição de Probabilidade da Matriz de Frequência: Uniforme


Dados gerados:

* Quantidade de sinistros por simulação
* Sinistro agregado por simulação
* Média do SAg
* Desvio-Padrão do SAg
* Quantidade de ocorrências que superaram a média do SAg
* Prêmio Estatístico
* prêmio puro por meio das Provisões Técnicas Carregadas, alfa = 25%
* Provisões Carregadas
* Prêmio Puro
* Probabilidade de ruína(epsilon) por solvência da companhia, Solvency II: épsilon = 0,5%
* Quantidade de ocorrências que superaram o percentil de solvência
* Histograma SAg x Frequência


Objetos de entrada:

* Carteira: Números de indivíduos compondo a carteira
* Cenários: Quantidade de cenários a serem simulados
* Probabilidade de Sinistro: Probabilidade de ocorrência de sinistro
* Severidade Média: Valor monetário esperado de indenização em caso de materialização do sinistro
* Distribuição de Probabilidade da Matriz Severidade: binária(Uniforme ou Exponencial) 

