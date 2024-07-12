### Dashboards Power BI <img width='25' height='25' src="https://img.icons8.com/?size=100&id=Ny0t2MYrJ70p&format=png&color=000000" />

#
#### Esse foi o projeto onde eu aprendi fazer:
- Importação do arquivo da base de dados da educação básica para o Power BI.
- Preparação dos dados.
- Leitura dos dados.
- Transformação dos dados.
- Ultilização do Power Query para conversão e remoção de linhas indesejadas e duplicadas, filtração de dados, manipulação de valores nulos.
- Criação da visualização.

#

#### Painel de Visualização Educação Básica

<img width='950' height='500' src="https://github.com/eduardolima17/PowerBI-pbix/blob/main/visualizacao-EducacaoBasica.png" />

#
#### Estrutura da base de dados

Arquivo em excel que contém as seguintes colunas:
- Região Geográfica
- Estado
- Município
- Código do Município
- Total de Matrículas
- Educação Infantil
- Ensino Fundamental
- Ensino Médio
- Educação Profissional

Nenhuma nova coluna foi criada a partir dos dados.
#
#### Quantidade de dados: 5.570
#

#### Painel de Visualização Analítico de Vendas Globais

<img width='950' height='500' src="https://github.com/eduardolima17/PowerBI-pbix/blob/main/visualizacao-VendaGlobais.png" />

Nesse Dashboard foi trabalhado com dados de vendas de uma empresa fictícia que comercializa produtos em todos os cantos do mundo.

Perguntas respondidas:
- Qual o valor total vendido?
- Quantas vendas foram realizadas por categoria de produto?
- Quantas vendas foram realizadas por país considerando a prioridade de entrega?
- Qual foi a média de desconto nas vendas por subcategoria de produto?
- Quais países tiveram maior média de valor de venda? Demonstre em um mapa.

#### Estrutura da base de dados

Arquivo em dataset csv que contém as seguintes colunas:
- Id Pedido
- Data Pedido
- Id Cliente
- Segmento
- País
- Id Produto
- Categoria
- Subcategoria
- Total Vendas
- Quantidade
- Desconto
- Lucro e Prioridade

#### Quantidade de dados: 51.290

#

#### Painel de Visualização Vendas, Lucros, Margemde de Lucros e KPI

<img width='950' height='500' src="https://github.com/eduardolima17/PowerBI-pbix/blob/main/visualizacao-VendasLucrosMargemdeLucroseKPI.png" />

Nesse Dashboard foi trabalhado com dados que contém vendas, lucros, margem de lucros e kpi.

Perguntas respondidas:

- Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata.
- Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.
- A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI–Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?
- Considere que o lucro é equivalente a:valor venda -custo envio. Qual categoria de produto apresentou maior lucro médio.
- Qual foi o comportamento da margem de lucro ao longo do tempo? Considere amargem de lucro como o lucro dividido pelo valor venda.

#### Estrutura da base de dados

Arquivos em dataset csv que contém as seguintes colunas:

#### csv clientes
- Cidade    
- Estado
- Id cliente
- Mercado
- Nome cliente
- País
- Região
- Segmento

#### csv pedidos
- Data envio
- Data pedido
- Id pedido
- Modo pedido
- Prioridade pedido

#### csv produtos
- Acessórios
- Id produto
- Tecnologia

#### csv vendas
- Cliente
- Custo envio
- Lucro
- Margem de lucro
- Pedido
- Produto
- Quantidade vendida
- Valor venda

#### Quantidade de dados: 88.207

