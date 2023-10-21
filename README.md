# Relatório do Desafio da DIO com Power BI

O projeto consciste na criação de um relatório de duas páginas em **Power Bi** que realiza o balanço financeiro de uma empresa 'fantasia'.

O projeto utiliza um conjunto de dados de exemplo chamado 'finantials' disponível dentro do [**_Power Bi Desktop_**](https://powerbi.microsoft.com/pt-br/downloads/).

Os tópicos abordados nesse relatório para essa empresa 'fantasia', foram:

- *Total de Vendas* (Cartões);
- *Total de Vendas Brutas* (Cartões);
- *Total de Descontos* (Cartões);
- *Total de COGS* (Cartões);
- *Lucro Total* (Cartões);
- *Total de Vendas por Mês* (Gráfico de Área);
- *Total de Vendas por Segmento* (Gráficos de Barra Clusterizado e Donuts);
- *Total de Vendas por Produto* (Gráfico de Barra Clusterizado);
- *Total de Vendas por Produto e País* (Gráfico de Barras e Mapa);
- *Lucro Total por País* (Árvore de Decomposição);
- *Lucro Total por Trimestre* (Gráfico de Cascata);
- *Lucro Total por Mês e Produto* (Gráfico de caixa de opções);
- *Lucro Total por Segmento* (Treemap);

### 📌📌 Observação:
**O que significa COGS?**

COGS é a abreviação de Cost of Goods Sold (EN) e se refere aos custos diretos de produção de produtos vendidos por uma empresa. Inclui o custo dos materiais e mão de obra utilizados para criar o produto. Exclui despesas indiretas, como custos de distribuição e custos de vendas.

Para saber mais sobre esse indicador/método click no link abaixo 👇🏾 

https://www.investopedia.com/terms/c/cogs.asp


## Screenshots do Relatório Gerado

Na primeira imagem a análise faz um detalhamento das vendas, mas já da um vislumbre dos lucros da empresa 'fantasia'.

![Imagem1_relatorio_dio](https://github.com/CarolFerr/desafio_PowerBi_dio/assets/114115953/68139e93-5e8c-48ec-b05f-ed4bb774ad0b)

Por outro lado, na segunda imagem a análise se concentra apenas nos lucros obtidos por essa empresa 'fantasia'.

![Imagem2_relatorio_dio](https://github.com/CarolFerr/desafio_PowerBi_dio/assets/114115953/64700ca3-99bb-4c59-bbe2-e38c3c2a256e)

Já a terceira imagem faz referência ao segundo relatório do segundo desafio de projeto que pede apenas para fazer alguns testes para verificar a integração do banco de dados criado na plataforma *Azure* e o *Power BI*, dessa forma foi criado alguns gráficos para se verificar essa integração e como ela se mantinha.

![Imagem1_relatorio2_dio](https://github.com/CarolFerr/desafio_PowerBi_dio/assets/114115953/fa622bf4-6bee-40c9-971d-f1d97e7760ef)

Mediante os testes propostos fez-se o questionamento.

❓ Ao mesclar os nomes da tabela departamentos e localização no power bi isso faz com que cada combinação departamento-local seja unico. Porque utilizar o mesclar e não o atribuir? 

**A resposta para essa pergunta é:**

Quando você mescla tabelas no Power BI, a operação de mesclagem não altera a estrutura das tabelas originais. Em vez disso, ela cria uma relação entre essas tabelas, permitindo que você consulte os dados combinados usando essa relação. Lembrando que a mesclagem de tabelas é útil quando você deseja relacionar informações de diferentes tabelas. Sendo assim, a razão pela qual não se realiza uma atribuição, como a criação de uma nova tabela contendo todas as combinações únicas de departamentos e localizações, durante a mesclagem, é a eficiência e a manutenção de dados.



## 📚 Documentação

- [*Azure*](https://azure.microsoft.com/pt-br)
- [*Power Bi*](https://learn.microsoft.com/pt-br/power-bi/)
- [*Digital Innovation One*](https://www.dio.me/en)



