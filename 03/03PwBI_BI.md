**03 - Business Intelligence no Power BI** 

**Web Scraping**

​	→ Acessar dados diretamente de páginas web 

​	→ Manipulação dos dados ( dar maior qualidade aos dados que chegam, ou seja tratar dados de forma mais adequada )

​	→ Ajustes são esperados pois grande parte dos dados não tem tratamento adequado. 

​	→ Pegar um site de base de dados e qual o tipo de acesso é realizado no site

*Query editor* é um editor de consultas (Somente clicar em editar consultas já o faz aparecer). 

* Transformar colunas em linhas (Faz junção de várias colunas zB. Ano e PIB)

  Técnicas de valor missing ( como interpolação linear e outras de estatística ) 

  NOTA: se der erro por causa de ',' ou '.' ir no menu "Arquivo", depois em "Opções e Configurações", escolha "Opções", depois na seção "Arquivo Atual", escolha "Configurações Regionais" e escolha o país de acordo com o país gerador dos dados.

  NOTA: Categoria de dados, indica se a coluna é um município ou um pais por exemplo. 

**Business Intelligence**

BI tem foco de mostrar o que aconteceu no passado enquanto data science tem foco em prever o que irá acontecer no futuro

*Exercício que será abordado durante os vídeos: Estudo de caso, Obtendo Relatório de Vendas Por Fabricante*

![](C:\Users\55319\AppData\Roaming\Typora\typora-user-images\1570809240864.png)



Implementações: 

1. Qual dos fabricantes apresenta melhor desempenho nas vendas.

   ​	→ Ou seja obter relatório de vendas por fabricante. (Saber qual fabricante gera mais retorno ou vendas consideráveis e significativas) 

2. Ter diferentes visões das vendas realizadas nos últimos 4 anos.  (2012 - 2015)

3. Relatórios serem extraídos sob demanda.



Necessário se preocupar com a melhor forma de obtenção das informações. Ou seja, gerar consultas mais performáticas possíveis. 

**Star Schema (Modelo de estrela)**

É o desenho de modelo relacional de um banco de dados.

→ Vertabelo é uma ferramenta para construção de modelo de dados.

Remover duplicatas em tabelas onde há relacionamentos 1 → n

Pois ao dividir a tabela ( DIM e FATO ) posso colocar as cardinalidades dos modelos. 

É possível adicionar novas medidas nos campos de relatórios

**Banco de dados não relacionado (NoSQL)**

Bancos de Dados tradicionais RDBMS (Relational Database Management Systems) não foram  projetados  para  tratar  grandes  quantidades  de  dados  não estruturados. Essa lacuna é preenchida por Banco de Dados NoSQL por ser mais escalável e eficiente

Bancos de Dados NoSQL oferecem 4 categorias de bancos de dados não-relacionais:

​	•Graph databases

​	•Document databases

​	•Key-values stores

​	•Column family stores

**Limpeza, Transformação, Séries Temporais, Agregação e Filtros**

Ué terminou aqui sem explicação boa