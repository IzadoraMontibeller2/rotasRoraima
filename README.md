Projeto de Mapeamento de Roraima para a Disciplina de Inteligência Artificial
Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial e tem como objetivo realizar o mapeamento do estado de Roraima, apresentando a rota mais curta para se chegar à capital, Boa Vista.

Visão Geral
O projeto utiliza o algoritmo A* (A-star) para encontrar a rota mais curta entre cidades no estado de Roraima. O algoritmo A* é uma forma eficiente de buscar o caminho ótimo em grafos, combinando a busca heurística e a busca de custo uniforme.

Funcionalidades
Mapeamento das cidades e suas respectivas distâncias até Boa Vista.
Determinação da rota mais curta para chegar a Boa Vista a partir de qualquer cidade do estado.
Utilização de heurística para estimar o custo restante até o destino.
Estrutura do Projeto
O projeto consiste em três classes principais:

City: Representa uma cidade do estado de Roraima, contendo seu nome, distância até Boa Vista e lista de vizinhos.
Neighbor: Representa um vizinho de uma cidade, contendo a referência para a cidade vizinha e a distância até ela.
RouteFinder: Classe principal que contém a lógica para encontrar a rota mais curta até Boa Vista utilizando o algoritmo A*.
Como Utilizar
Clone este repositório em sua máquina local.
Abra o projeto em sua IDE Java preferida.
Execute a classe RouteFinder.java.
O programa irá calcular e exibir a rota mais curta para chegar a Boa Vista a partir de cada cidade do estado.
