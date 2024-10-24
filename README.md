# Modelando_um_Dashboard_de_E-commerce_c_PowerBI
 Modelando um Dashboard de E-commerce com Power BI

1. Etapas da Construção
Importação de Dados: Os dados foram trazidos de diferentes fontes e centralizados no Power BI.

Modelo Relacional (Esquema em Estrela): O modelo foi organizado em:

Tabela Fato: Contém as transações financeiras (vendas, valores, datas).
Tabelas Dimensões: Informações sobre clientes, produtos, categorias e datas.
Transformação de Dados: Os dados foram limpos e transformados usando o Power Query, criando novas colunas e organizando as informações para melhor visualização.

2. Funcionalidades
Dashboards Interativos: Visualização de KPIs (lucro, vendas, margem) com filtros por período, cliente e produto.

Filtros Dinâmicos: Segmentação por diferentes dimensões, como cliente, produto e datas, permitindo análises detalhadas.

Indicadores Personalizados: Cálculo de crescimento percentual de vendas, margem de lucro, entre outros.

3. Funções DAX Utilizadas
Agregações:

SUM(): Soma valores de colunas como total de vendas.
AVERAGE(): Média dos valores, como vendas médias por categoria.
Filtros:

CALCULATE(): Para cálculos com condições específicas.
FILTER(): Filtra os dados para aplicar condições personalizadas.
Inteligência de Tempo:

SAMEPERIODLASTYEAR(): Compara valores com o mesmo período do ano anterior.
Condicionais:

IF(): Cria condições, como "Bom" ou "Ruim", baseado em indicadores.
