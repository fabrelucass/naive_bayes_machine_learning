Classificação de Dados com Modelos Naive Bayes e Random Forest

Este repositório implementa a classificação de dados utilizando três variantes do modelo Naive Bayes (GaussianNB, MultinomialNB, BernoulliNB) e o Random Forest. O código realiza pré-processamento de dados, validação cruzada, ajuste de hiperparâmetros, e avaliação de desempenho com métricas como acurácia e matriz de confusão.

Funcionalidades

Pré-processamento de Dados: Limpeza e normalização dos dados para melhorar a precisão dos modelos.
Treinamento de Modelos: Treinamento com os algoritmos Naive Bayes (Gaussian, Multinomial e Bernoulli) e Random Forest.
Validação Cruzada: Validação cruzada para avaliar a robustez dos modelos.
Ajuste de Hiperparâmetros: Ajuste de hiperparâmetros usando o GridSearchCV para encontrar os melhores parâmetros.
Avaliação de Modelos: Cálculo de métricas como acurácia e a matriz de confusão para avaliar a performance dos modelos treinados.

Estrutura do Projeto

Pré-processamento: Funcionalidades para limpar e normalizar os dados.
Treinamento de Modelos: Implementações dos modelos Naive Bayes (Gaussian, Multinomial, Bernoulli) e Random Forest.
Ajuste de Hiperparâmetros: Utilização de GridSearchCV para otimizar os parâmetros do modelo.
Validação Cruzada: Realização de validação cruzada para avaliar a performance dos modelos.
Avaliação de Desempenho: Geração de métricas como acurácia e matriz de confusão.

Como Usar
Clone este repositório em sua máquina.

Instale as dependências necessárias:


pip install -r requirements.txt

Execute o código em um ambiente de sua escolha:

python main.py
Dependências
scikit-learn: Para os modelos de machine learning e validação cruzada.
pandas: Para manipulação de dados.
numpy: Para operações numéricas.
matplotlib e seaborn: Para visualização de resultados.

Contribuição
Sinta-se à vontade para abrir issues ou pull requests se quiser contribuir para o projeto. Qualquer ajuda é bem-vinda!
