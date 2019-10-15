**02 - Power BI Desktop** 

 **Integrações:** 
    → Linguagem R 
    → Apache Spark (Funciona como um banco de dados para BIG DATA)
    → Oracle e SQL server são os principais

  **Ambiente de Desenvolvimento em Data Science (Windows):** 
    → Power BI Desktop
    → JDK
    → VM (maquinas virtuais diferentes)
    → Instalar linguagem R 
    → Instalar Python

Nota: Só funciona com e-mails corporativos ou de estudante. 

**Fontes de Dados do Power BI:** 
    → Excel
    → CSV
    → Oracle SQL
    → Github

**Carregar Arquivos CSV e Excel:**
    → Puxar de um arquivo base e escolher UTF8 nele. 

**Workflow (Fluxo de trabalho):**
    → Definição do problema (Escolher algoritmos e modelos)
    → Buscar dados que ajudaram a resolver o problema (Preparação → Modelagem → Visualização)
    → Preparação dos dados com Query Editor
    → Modelagem dos dados com Relatonship View 
    → Visualização dos Dados com Report View

**Explorar Dados:**

​    Estudo de caso & definição de problema de negócio

​	*Exercício que será abordado durante os vídeos: construção e abordagem de dados*

​	Dashboard que represente os dados de vendas no período 2012 a 2015.

​	Fonte de dados → Excel com as colunas.: 

​	

| Coluna           | Descrição                                          |
| ---------------- | -------------------------------------------------- |
| *DataNotaFiscal* | Data de emissão da nota fiscal                     |
| *Fabricante*     | Fabricante do veículo                              |
| *Estado*         | Estado onde foi realizada a venda                  |
| *PrecoVenda*     | Preço de venda do veículo                          |
| *PrecoCusto*     | Preço de custo do veículo para a empresa           |
| *TotalDesconto*  | Total de desconto fornecido sobre o preço de venda |
| *CustoEntrega*   | Custo de entrega do veículo ao proprietário        |
| *CustoMaoDeObra* | Custo de mão de obra (funcionários)                |
| *NomeCliente*    | Nome do cliente que comprou o veículo              |
| *Modelo*         | Modelo do veículo                                  |
| *Cor*            | Cor do veículo                                     |
| *Ano*            | Ano de fabricação do veículo                       |

Seu gerente precisa das seguintes informações: 

1. Total de vendas por ano 	
2. Custo de entrega do veículo por fabricante
3. Custo de mão de obra por estado
4. Total de vendas geral e matriz de vendas

NOTA: CEO deseja visualizar o total de vendas por estado e se as vendas estão acima ou abaixo da média, estão avaliando se continuam ou não com a venda de automóveis da marca Jaguar e a ideia é saber o quanto evoluíram as vendas deste automóvel por ano e estado. 

**Construir Visualizações:**
    → Selecionar o tipo de gráfico ou de forma de visualizar os dados inseridos no PwBI.

​	→  Algumas vezes é necessário fazer alterações de tipo para acertar o formato dos dados. 

​	→ *Dashboards* , deve conter apenas os elementos mais importantes da história, ou seja detalhamento dos dados. (Também tem curso na data science)

Nota: Hierarquia é o que indica a forma do dado ser mostrado, exemplo por ano,mês ou dia.

*Exercício que será abordado durante os vídeos: Construção do dashboard*

​	→ Criação do dashboard de acordo com as especificações. 

| Especificação | Tipo de Dashboard                                 |
| ------------- | ------------------------------------------------- |
| 1             | Gráfico de barras                                 |
| 2             | Gráfico de Pizza                                  |
| 3             | Mapa é uma boa                                    |
| 4             | Cartão (total de vendas) Matriz (é a sua escolha) |

**Formatar Legenda, Título e Labels:**
    → Em cada campo escolhido na Dashboard pode ser modificado.

**Publicação de dashboard online:** 

​	→ Somente clicar em publicar no online, ai receberá link do dashboard online.