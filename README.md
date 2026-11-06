# Spring Project: Classificação de Flores

Conforme delineado no código e na referência image_c9194c.png, este projeto consiste numa tarefa de classificação de cinco tipos de flores: Girassol (Sunflower), Margarida (Daisy), Dente-de-leão (Dandelion), Tulipa (Tulip) e Rosa (Rose). Para esta tarefa, foi utilizado o seguinte conjunto de dados: (https://www.kaggle.com/datasets/rishitchs/final-flowers-course-project-dataset).


## Metodologia e Etapas do Projeto
* Análise Exploratória: Realização de uma análise inicial aos dados, onde se constatou que o número de imagens disponíveis era inferior ao necessário para um treino ideal.

* Aumento de Dados (Data Augmentation): Utilização da ferramenta ImageDataGenerator para gerar novas amostras a partir das imagens originais (aplicando rotações, inversões e zoom) com o objetivo de colmatar a escassez de dados.

* Modelagem: Desenvolvimento de uma Rede Neural Convolucional (CNN), uma arquitetura naturalmente indicada para o processamento de imagens, construída com várias camadas de convolução, pooling, dropout e normalização.

* Validação Cruzada: Aplicação do método Stratified K-Fold (com 5 partições) para melhorar a aprendizagem da rede e avaliar o modelo de forma mais robusta.

* Avaliação: Geração de matrizes de confusão, relatórios de classificação e gráficos de evolução da exatidão (accuracy) e perda (loss).


## Bibliotecas Utilizadas

* Ambiente: Python (Google Colab)

* Machine Learning e Redes Neurais: TensorFlow, Keras, Scikit-learn

* Manipulação de Dados: Pandas, NumPy

* Visualização: Matplotlib, Visualkeras
