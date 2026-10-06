# Análise de Dados de E-commerce Brasileiro

Análise exploratória de dados de e-commerce brasileiro usando Python, Pandas, NumPy, Matplotlib e Seaborn para identificar tendências de vendas, comportamento de clientes e insights de negócio.

## Objetivo do Projeto

Analisar dados de e-commerce e identificar padrões de volume de pedidos, pagamentos, categorias de produtos e localização dos clientes.

## Conjunto de Dados

Brazilian E-Commerce Public Dataset by Olist, com 99.441 pedidos entre set/2016 e out/2018. Neste projeto foram usadas 6 tabelas: pedidos, itens, pagamentos, produtos, clientes e tradução de categorias.

Os dados estão disponíveis no Kaggle (busque por "Brazilian E-Commerce Public Dataset by Olist"). Baixe os arquivos CSV e coloque-os na pasta `data/raw/` para rodar o notebook.

## Ferramentas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Principais Análises

- Volume de pedidos ao longo do tempo
- Volume mensal de pagamentos
- Ticket médio (valor médio por pedido)
- Distribuição dos valores de pagamento
- Desempenho por categoria de produto
- Análise geográfica por estado

## Principais Insights

- Os pedidos somaram R$ 16 milhões em pagamentos, com ticket médio de R$ 161.
- Novembro de 2017 teve o maior volume de pedidos (7.544), 63% acima de outubro.
- O pico de novembro veio do aumento no número de pedidos, e não do valor gasto por pedido.
- A maioria dos pagamentos tem valor baixo, e poucos pagamentos muito altos puxam a média para cima.
- A categoria *bed_bath_table* vendeu mais itens (11.115), mas *health_beauty* teve a maior receita (R$ 1,26 milhão).
- São Paulo lidera tanto em número de pedidos quanto em valor total pago.
- Setembro de 2018 tem só 16 pedidos e foi tratado com cautela nas comparações.

## Estrutura do Projeto

```text
ecommerce-data-analysis/
├── ecommerce_analysis.ipynb
├── README.md
└── .gitignore
```
