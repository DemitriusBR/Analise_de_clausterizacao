# Análise de Clustering de Clientes em E-commerce

## Descrição do Projeto

Este projeto tem como objetivo desenvolver um modelo de clusterização para segmentar clientes de um e-commerce com base em suas métricas de comportamento de compra, utilizando a metodologia RFV (Recência, Frequência e Valor). O modelo permitirá à empresa personalizar suas campanhas de marketing, oferecendo promoções direcionadas aos diferentes perfis de clientes.

## Introdução

O crescimento do e-commerce tornou essencial a compreensão do comportamento dos clientes. A análise por cluster permite identificar padrões e criar estratégias de marketing mais eficazes.

## Objetivos

- Agrupar clientes com base em suas métricas de compra (RFV).
- Identificar perfis de clientes para personalizar campanhas de marketing.
- Fornecer insights acionáveis para melhorar o desempenho do e-commerce.

## Dados Utilizados

Os dados foram extraídos de um conjunto disponível no Kaggle, contendo transações de uma loja de e-commerce entre 2010 e 2011. As principais colunas analisadas foram:

- **InvoiceNo**: Identificação da transação
- **StockCode**: Código do produto
- **Description**: Descrição do produto
- **Quantity**: Quantidade comprada
- **InvoiceDate**: Data da transação
- **UnitPrice**: Preço unitário
- **CustomerID**: Identificação do cliente
- **Country**: País de origem

## Resumo dos repositorios

-  **Base**: Liberação do dados e as informações que a compoem
-  **Projeto_att.ipynb**: Jupyter Notebook que documenta todo o processo de análise e clusterização, desde a exploração inicial dos dados até a implementação do modelo de clustering. O notebook apresenta visualizações e explicações detalhadas de cada etapa metodológica aplicada.
-  **Resumo do Projeto**: Visão geral das ações realizadas
-  **Insights**: Apresentação das conclusões que foram retiradas a partir projeto

## Conclusões e Recomendações

- A segmentação de clientes pode levar a um aumento nas taxas de conversão.
- Recomenda-se a personalização de campanhas de marketing com base nos clusters identificados.
- Monitoramento contínuo do comportamento do cliente e atualização do modelo de clusterização.

## Referências

- Conjunto de dados do Kaggle: [E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- Literatura sobre Análise de Cluster e RFV.
