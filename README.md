# Projeto: Funcionamento do KNN (K-Nearest Neighbors)
## Descrição
Este projeto tem como objetivo demonstrar na prática o funcionamento do algoritmo KNN (K-Nearest Neighbors), um dos métodos mais simples e eficazes para classificação e regressão em Machine Learning. Através de exemplos práticos e visualizações claras, o projeto explora desde os conceitos básicos até a aplicação em um cenário real com o famoso dataset Iris.

### O KNN é um algoritmo de aprendizado supervisionado que classifica novos pontos de dados com base na similaridade com os exemplos de treinamento. Este notebook cobre:

- Importação e preparação de dados

- Visualização dos dados

- Aplicação do KNN em um dataset artificial criado para fins didáticos

- Utilização do KNN com o dataset Iris para um cenário real

- Separação dos dados em treino e teste

- Visualização dos resultados

## Modelo K-Nearest Neighbors (KNN) - Explicação e Implementação
O K-Nearest Neighbors (KNN) é um algoritmo simples de aprendizado supervisionado usado para classificação e regressão. Ele se baseia no princípio de que objetos similares estão próximos no espaço de features.
________________________________________
### Como o KNN Funciona?
1.	Calcula distâncias entre o novo dado e todos os pontos no conjunto de treino.
2.	Seleciona os K vizinhos mais próximos (onde K é um hiperparâmetro).
3.	Para classificação: A classe mais frequente entre os K vizinhos é atribuída.
4.	Para regressão: A média dos valores dos K vizinhos é calculada.
