# Análise de Comportamento de Clientes com Segmentação RFM

## Objetivo do Projeto
O objetivo deste projeto é analisar o comportamento dos clientes utilizando a técnica de segmentação RFM (Recência, Frequência e Valor Monetário) para otimizar estratégias de marketing.

## Resumo das Etapas

### 1. Análise Estatística Inicial
- Utilização de `describe()` e `info()` para obter uma visão geral das estatísticas e estrutura dos dados.

### 2. Limpeza de Dados
- Remoção de colunas desnecessárias.
- Eliminação de duplicatas e linhas com valores nulos ou inválidos (quantidades e preços negativos).

### 3. Criação de Novas Colunas
- Cálculo do valor total gasto em compras.
- Conversão de tipos de dados para garantir a consistência.

### 4. Análise de Outliers
- Identificação e remoção de outliers nas colunas 'Quantity' e 'UnitPrice'.
- Realização de uma nova análise estatística.

### 5. Cálculo de Métricas RFM
- Cálculo de recência, frequência e valor monetário para cada cliente, resultando em um DataFrame que combina essas métricas.

### 6. Segmentação com K-means
- Aplicação do algoritmo K-means para segmentar os clientes em clusters com base nas métricas RFM.
- Visualização dos clusters em um gráfico 3D.

### 7. Avaliação de Clusters
- Uso do método do Elbow e do Silhouette Score para determinar o número ideal de clusters.

### 8. Análise de Correlação
- Cálculo e visualização da matriz de correlação entre as variáveis para entender suas interações.

### 9. Identificação de Novos Clientes
- Análise da distribuição de novos clientes com base na recência, visualizando o impacto do tempo desde a última compra.

### 10. Gráficos de Dispersão
- Criação de gráficos de dispersão para explorar a relação entre recência e frequência, utilizando o valor monetário para determinar o tamanho e a cor dos pontos.

## Função do Projeto
Este projeto visa segmentar a base de clientes para entender melhor seus comportamentos de compra. Ao utilizar as métricas RFM, ele ajuda a identificar grupos de clientes que podem ser alvos de campanhas de marketing mais eficazes. Além disso, a análise de outliers e a visualização dos dados proporcionam insights valiosos sobre a saúde das vendas e o comportamento dos consumidores, permitindo tomadas de decisões informadas para melhorar a retenção e a aquisição de clientes.


## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
