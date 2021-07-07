# DecisionTree
## Implementando o classificador C4.5 - Arvore de  Decisão

1) Banco de dados: Wine
- 13 atributos contínuos. 3 classes (tipos de vinho – “1ª coluna do arquivo wine.csv”).
- 178 amostras: 59 da classe 1, 71 da classe 2 e 48 da classe 3.

2) Classificadores
2.1) Implementar o classificador: C4.5 
- Deve usar a entropia (ganho de informação) como critério de escolha dos nós 
- Não é necessário realizar as podas
- Você deve escolher os atributos que achar mais convenientes.
- Deve-se usar pelo menos 4 atributos. 
- Não usar funções prontas do Matlab/Python para o C4.5


3) Experimento com o algoritmo C4.5 (fazer 10 realizações)
a) Realização:
- Dividir dados, aleatoriamente, entre treinamento e teste.
 (Ex: 80% para treino, 20% para teste)
- Contrói o modelo com os dados de treinamento
- Verifica a acurácia (taxa de acerto) do modelo (teste).
b) Estatística:
- Calcular a taxa de acerto média das 10 realizações
