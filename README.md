# Sobre o projeto

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Caiojosue/Bot-Pedbot/blob/main/LICENSE)

Esse é um modelo de previsão de vendas com Machine Learning, que tem como objetivo Desenvolver um modelo de machine learning capaz de prever as vendas futuras de uma empresa ou loja, utilizando dados históricos de vendas e outras variáveis relevantes, o objetivo auxiliar na tomada de decisões estratégicas, como planejamento de estoque, marketing, e otimização de recursos

## Etapas do projeto

### Coleta e Preparação dos Dados

Reunir dados históricos de vendas, incluindo informações como data, produto, quantidade vendida, preço, promoções, sazonalidades, etc...
Limpeza dos Dados: Tratar valores ausentes, remover duplicatas, corrigir inconsistências e realizar normalizações necessárias, Feature Engineering: Criar novas variáveis (features) que possam ser relevantes para o modelo, como tendências, médias móveis, indicadores econômicos, fatores sazonais, etc

### Análise Exploratória dos Dados (EDA) 

Analisar padrões históricos de vendas, identificar sazonalidades, tendências e outliers
Visualizar a correlação entre diferentes variáveis, como preços, promoções e volumes de vendas

### Selecionar e Treinar Modelos de Machine Learning

- Divisão dos Dados: Separar os dados em conjuntos de treinamento e teste

- Modelos: Testar diferentes algoritmos de machine learning, como Regressão Linear, Árvores de Decisão, Random Forest, XGBoost, e Redes Neurais

- Treinamento: Treinar os modelos nos dados históricos

- Hiperparâmetros: Ajustar os hiperparâmetros para melhorar a performance dos modelos

### Avaliação do Modelo

- Utilizar métricas de avaliação como MAE (Mean Absolute Error), RMSE (Root Mean Squared Error) e R² para medir a precisão das previsões.

- Comparar o desempenho dos diferentes modelos e selecionar o melhor


### Validação Cruzada e Testes

- Realizar validação cruzada para garantir que o modelo generalize bem para dados não vistos

- Testar o modelo em um conjunto de dados de teste separado para verificar sua eficácia


### Implantação do Modelo

- Integrar o modelo ao sistema de vendas da empresa, permitindo que previsões sejam feitas regularmente

- Desenvolver uma interface ou dashboard para que os usuários possam visualizar as previsões de vendas de forma clara e intuitiva


# Resultados esperados

- Previsões de vendas mais precisas, permitindo melhor planejamento de estoque e produção
  
- Redução de perdas por excesso de estoque ou falta de produtos
  
- Aumento na eficiência operacional e nas margens de lucro através de decisões baseadas em dados

# Executando o Projeto

https://github.com/user-attachments/assets/d8aae7f2-e031-46ba-8d53-58a8fb6278ab


```bash
df_original = pd.read_csv('online_shoppers_intention.csv')
df_original.head()
```
### Comando para executar a planilha em .csv "lembrando que o arquivo deve estar na mesma pasta que o modelo"

# Considerações Finais

O sucesso do projeto depende da qualidade dos dados e da escolha adequada do modelo de machine learning, a colaboração entre especialistas de negócios e cientistas de dados é crucial para a correta interpretação dos resultados e para a implementação eficaz do modelo no ambiente de negócios

## Imagens do Modelo 

![Imagem1](https://github.com/Caiojosue/imagens/blob/main/Sem%20t%C3%ADtulo.png)

![Imagem2](https://github.com/Caiojosue/imagens/blob/main/Sem%20t%C3%ADtulo1.png)

![Imagem3](https://github.com/Caiojosue/imagens/blob/main/Sem%20t%C3%ADtulo2.png)

![Imagem4](https://github.com/Caiojosue/imagens/blob/main/Sem%20t%C3%ADtulo3.png)

![Imagem5](https://github.com/Caiojosue/imagens/blob/main/boxplot2.png)

![Imagem6](https://github.com/Caiojosue/imagens/blob/main/boxplot1.png)

# Autor

Caio Josué Ferreira de Sando

### Linkedin
https://www.linkedin.com/in/caio-sando-14ba1a2b5/
