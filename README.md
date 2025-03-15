
# Previsão de Congestionamento de Tráfego

Previsão de congestionamento de tráfego usando análise de dados, inferência estatística e aprendizado de máquina.

## Objetivo

Desenvolver um modelo preditivo preciso para auxiliar na gestão do tráfego urbano, otimizando rotas e reduzindo congestionamentos.

## Processo

* **Coleta de dados:**
    * "Este conjunto de dados, alimentado por um modelo de visão computacional, oferece um retrato detalhado do tráfego. Ele contabiliza carros, bicicletas, ônibus e caminhões a cada 15 minutos, registrando a hora, data e dia da semana."
    * "Além do número total de veículos, o conjunto classifica o tráfego em quatro níveis (baixo, normal, alto e pesado), fornecendo uma visão completa da movimentação em um período de um mês."
    * **Fonte de dados:** [Traffic Prediction Dataset - Kaggle](https://www.kaggle.com/datasets/hasibullahaman/traffic-prediction-dataset)

* **Análise exploratória de dados (EDA):**
    * "A EDA foi realizada para identificar padrões e tendências nos dados, utilizando visualizações e estatísticas descritivas."
* **Inferência estatística:**
    * "Foram realizadas análises de variância (ANOVA) para determinar se existem diferenças estatisticamente significativas entre os níveis de tráfego (baixo, normal, alto e pesado) em relação a diferentes variáveis, como dia da semana e hora do dia. O teste de Tukey foi aplicado para realizar comparações múltiplas entre as médias dos grupos, identificando quais níveis de tráfego diferem significativamente entre si."
* **Modelagem de aprendizado de máquina:**
    * "Modelos classificação foram treinados e avaliados para prever a ocorrência de congestionamentos."
    * (os algoritmos usados foram regressão logistica, random forest, svm, knn)
* **Avaliação e resultados:**
    * "O desempenho do modelo de aprendizado de máquina foi avaliado utilizando as seguintes métricas:
        * **Cohen's Kappa Score:** Mede a concordância entre as previsões do modelo e os valores reais, levando em consideração a concordância aleatória.
        * **Recall (Sensibilidade):** Indica a capacidade do modelo de identificar corretamente todos os casos positivos (congestionamentos).
        * **Precision (Precisão):** Indica a proporção de previsões positivas corretas em relação a todas as previsões positivas.
        * **Matriz de Confusão:** Apresenta uma visão detalhada do desempenho do modelo, mostrando o número de previsões corretas e incorretas para cada classe (nível de tráfego)."
    * (Se você tiver resultados numéricos específicos para essas métricas, como valores de Kappa, recall, precision e a matriz de confusão, inclua-os aqui. Por exemplo: "O modelo alcançou um Kappa de 0.85, recall de 0.92 e precision de 0.88.")

## Ferramentas

* **Linguagens de programação:**
    * Python
* **Bibliotecas:**
    * Pandas
    * NumPy
    * Scikit-learn
    * Matplotlib
    * Seaborn


