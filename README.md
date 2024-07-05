## Classificação Multilabel e Regressão em um Contexto Cinematográfico

Este projeto implementa uma solução de classificação multilabel e regressão para prever os gêneros de um filme e analisar o faturamento com base na descrição do filme. Utilizamos vários algoritmos de aprendizado de máquina, incluindo Random Forest, K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Logistic Regression e Gradient Boosting.

### Como instalar

1. Clone este repositório para sua máquina local.
2. Certifique-se de ter o Python instalado em sua máquina. Este projeto requer Python 3.7 ou superior.
3. Instale as dependências do projeto. No terminal, navegue até o diretório do projeto e execute o comando: `pip install -r requirements.txt`.

### Como executar o projeto

1. No terminal, navegue até o diretório do projeto.
2. Execute os codigos do notebook `LH_CD_GESSICASILVA.ipynb`.

### Sobre o código

O código realiza várias etapas para prever os gêneros de um filme e analisar o faturamento com base na descrição do filme:

1. **Preprocessamento de dados**: Limpeza e lematização do texto.
2. **Vetorização**: Transformação do texto em uma representação numérica usando TF-IDF.
3. **Modelagem**: Treinamento de vários modelos de aprendizado de máquina e avaliação de seu desempenho.
4. **Otimização de hiperparâmetros**: Ajuste dos hiperparâmetros dos modelos para melhorar seu desempenho.
5. **Análise de faturamento**: Análise da correlação entre o número de votos e o faturamento do filme.
6. **Análise de gênero**: Análise da distribuição de filmes por gênero e identificação das palavras mais importantes para cada gênero.
