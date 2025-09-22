# PROJETO STAR SCHEMA - DIO

## O que é o Star Schema (Esquema Estrela)?

O **Star Schema**, ou Esquema Estrela, é um modelo de dados multidimensional utilizado em *Data Warehouses* e *Business Intelligence*. Sua estrutura é otimizada para consultas e análises, sendo composta por:

- **Tabela Fato:** Localizada no centro do "esquema", armazena as métricas e os dados quantitativos de um processo de negócio (ex: vendas, faturamento, quantidade). Ela contém chaves estrangeiras que a conectam às tabelas de dimensão.
- **Tabelas de Dimensão:** São tabelas que se conectam à tabela fato e contêm os atributos descritivos relacionados aos dados. Elas fornecem o contexto para as métricas da tabela fato (ex: dimensão de tempo, produto, cliente, localidade).

A simplicidade e a desnormalização parcial deste modelo resultam em consultas mais rápidas e de fácil compreensão, sendo um dos modelos mais populares para a construção de relatórios e dashboards analíticos.
