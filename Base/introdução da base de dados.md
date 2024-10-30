## Sobre os Dados

Você pode acessar os dados [aqui](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

Os dados fornecidos contêm informações sobre transações de compras de uma loja de e-commerce em 38 países e territórios, incluindo mais de 4.000 clientes únicos e mais de 540.000 transações.

### Observações Importantes:
- **Formato das Datas:** As datas estão no formato MM/DD/YYYY HH:mm:ss.
- **Tratamento de Dados Nulos:** Existem dados nulos que precisam ser tratados antes da realização da análise.
- **Identificadores Numéricos:** Embora os códigos de identificação sejam numéricos, o modelo não deve considerá-los como grandezas numéricas.

## Estrutura dos Dados

A tabela de dados contém as seguintes colunas:

| Coluna      | Descrição                                   | Tipo     |
|-------------|---------------------------------------------|----------|
| InvoiceNo   | Identificação da transação                  | Int      |
| StockCode   | Código de estoque do produto                 | String   |
| Description | Descrição do produto                         | String   |
| Quantity    | Quantidade de produtos por transação        | Int      |
| InvoiceDate | Data da transação                           | Datetime |
| UnitPrice   | Preço unitário do produto                   | Float    |
| CustomerID  | Identificação do cliente                     | Int      |
| Country     | País de origem da transação                 | String   |
