<div style="background-color: lightgreen; padding: 10px;">
    <h2> Projeto | Machine Learning I - Problema de Classificação
</div>

### Aluno:
André R. Kuster | nº: 1116029

### Objetivo:

Este projeto visa aplicar os conceitos aprendidos na disciplina de **Machine Learning 1** em um contexto prático, usando um conjunto de dados disponível no Kaggle Datasets. Nosso objetivo é praticar a implementação de um algoritmo de classificação utilizando a biblioteca Scikit-learn, calcular as métricas de avaliação dos modelos e otimizar os hiperparâmetros.

### Base de Dados:
Será utilizado conjunto de dados de clientes de uma empresa de telecomunicação. A base contém variáveis explicativas (features) sobre a assinatura, sobre o uso dos serviços contratados pelos clientes, como número de chamadas durante o dia, durante a noite, bem como uma informação sobre o número de chamados no suporte que esse cliente fez. A variável dependente (target) consiste no **churn**, que é positivo caso o cliente tenha cancelado a sua assinatura, enquanto o negativo representa um cliente ativo.

### Motivação:

A motivação do projeto é comparar a performance dos algoritmos **KNN** e **Random Forest** para um problema de classificação antes e depois da otimização de hiperparâmetros e chegar a uma conclusão sobre o modelo que melhor performou.

![lego-unsplash.jpg](attachment:84a7cc10-1a02-493d-847c-a2781590305c.jpg)
Foto de <a href="https://unsplash.com/pt-br/@helloimnik?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Nik</a> na <a href="https://unsplash.com/pt-br/fotografias/brinquedo-plastico-redondo-amarelo-e-branco-zYdYz7JlevE?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>

### Ferramentas:
NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

### Referências:
- https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets/datae
- https://scikit-learn.org/stable/modules/neighbors.html
- https://scikit-learn.org/stable/modules/tree.html
- https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html
- https://scikit-learn.org/stable/modules/model_evaluation.html#scoring
- https://caiquecoelho.medium.com/um-guia-completo-para-o-pr%C3%A9-processamento-de-dados-em-machine-learning-f860fbadabe1
- https://www.datacamp.com/tutorial/k-nearest-neighbor-classification-scikit-learn
- https://www.datacamp.com/tutorial/random-forests-classifier-python
- https://icmcjunior.com.br/random-forest/#:~:text=O%20que%20%C3%A9%20Random%20Forest,para%20chegar%20no%20resultado%20final.
