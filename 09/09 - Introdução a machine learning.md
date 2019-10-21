**09 - Introdução a machine learning **

 Big Data se refere ao conjunto de dados definido pelos 4 V’s: volume,variedade, velocidade e veracidade. A extração do conhecimento se dá através de técnicas como Data Science por exemplo. A melhor maneira para falar de metodologias e tecnologias em Big Data é utilizar  a  expressão  Analytics,que  pode  ser  definida  como  o  uso  da  tecnologia  para  a compreensão, comunicação e utilização inteligente dos dados digitais.

![4-Vs-of-big-data](C:\Users\55319\Desktop\DS_PwBI\09\4-Vs-of-big-data.jpg)

*fonte: IBM*

Contudo o termo Analytcs também pode ser divídido em 4 áreas fundamentais.

1. Análise Descritiva → Se encarrega de analisar o que aconteceu. 
2. Análise Diagnóstica → Analisa por que determinado evento aconteceu. 
3. Análise Preditiva → Aponta o que irá ou poderá acontecer no futuro. 
4. Análise Prescritiva → Analisa o que se deseja que aconteça e o que pode ser feito para alcançar tal objetivo. (reforçar, modificar ou evitar uma predição.)

A humanidade vem gerando dados como nunca antes na história, por este motivo hoje em dia conseguimos fazer predições sobre os dados que desde sempre existiam, mas não podiam ser feitas por baixa quantidade de dados existentes. 

**O que é aprendizagem de máquina?**

*Scikit learning - Python*

*Apache Mahout - Php*

*Spark ml lib -*

*Tensor flow - do Google*

→ Curso de machine learning pode ser útil. 

* Adaptação : Mudança de comportamento evolutiva, ou seja seguindo critérios. 
* Correção : Não repetir erros que já foram cometidos no passado. 
* Otimização : Melhoria da performance do sistema como um todo, ou seja, desde redução de energia até o tempo gasto em uma tarefa.
* Representação : Armazenar e representar o conhecimento adquirido durante o aprendizado. 
* Interação : Como é trocada experiência com o meio para gerar aprendizagem de máquina?  

→ *Machine learning* é um subcampo da inteligência artificial, pois dá aos computadores a habilidade de aprender sem que sejam explicitamente programados para isso. 

**Tipos de aprendizagem de máquina**

(1) Supervisionada → Dou uma entrada e uma saída.

(2) Não-supervisionada → Não sei a saída. 

(3) Semi-supervisionada → Combinação. 

(4) Por reforço → Muito utilizada em games.

(5) Deep learning → Aprendizagem profunda. 

1. **Aprendizagem Supervisionada**, ocorre quando um alg. aprende com dados de exemplo, dados de entrada e dados de saída. Mais semelhante a uma aprendizagem humana, ou seja, um professor ensina e um aluno grava tanto que aprende. 

   → Dados de treino → Alg. de Machine Learning 

   Novos dados → **Modelos preditivos** → Previsões (Ou seja com base nos dados de treino é possível utilizar modelos preditivos para realizar previsões) 

   Bom exemplo: Banco de dados sobre bolsa de valores. 

   1. Classificação, são usados geralmente quando previsões são de naturezas distintas. 
   2. Regressão, são usados quando os valores previstos diferem de sim ou não, exemplo, valores previstos como, quanto irá custar tal produto em um tempo.
   3. Detecção de anomalias, exemplo ações fraudulentas de cartão de crédito. 

Logo aprendizagem supervisionada é sempre utilizado quando o programa tem que ser "treinado" sobre um conjunto de dados pré-definido. 

2. **Aprendizagem não-supervisionada**, ocorre quando um alg. aprende com exemplos simples mas sem nenhuma resposta associada, ou seja o alg. determina os padrões de dados por conta própria, tendência a reestruturar os dados com novos atributos que podem então representar uma classe ou uma nova série de valores não relacionados, úteis para fornecer insights sobre o significado dos dados.  Exemplo, buscar padrões de grupos de clientes, alg. de recomendações. (Mapas auto-organizáveis, agrupamento k-means)

Logo aprendizagem não-supervisionada é utilizado quando um programa pode automaticamente encontrar padrões e relações em um conjunto de dados. 

3. **Deep Learning** (redes neurais profundas), (ATÉ ENTÃO não gostei da explicação) é utilizado para descrever o processo de utilizar modelos de redes neurais de múltiplas camadas. Rede covolucional, rede neural recorrente. Bastante sucesso para resolver problemas de visão computacional. 

**Treinamento Validação e Teste**

Processo de aprendizagem humana reproduzido matematicamente para a máquina.

Subsets dos dados: 

​	→ Dados de treino 70% dos dados

​	→ Dados de teste 30% dos dados (Caso exista teste de validação 20% são para validação - problemas de overfiting)

Alg. de Aprendizagem → Modelo → Testes → Índice de performance. 

*Cross validation* → Serve para preparação de modelos preditivos. 

Realizar análise exploratória dos dados, afim de entendimento completo dos dados em si (Se precisa transformar colunas, ou binarizar, essas coisas).

Modelo → representação dos dados de forma de algoritmo.  

![opera_s68bR6IuPx](C:\Users\55319\Documents\ShareX\Screenshots\2019-10\opera_s68bR6IuPx.png)

O processo tem de ser feito várias e várias vezes até conseguir o resultado desejado.

Logicamente: Cada modelo requer um modelo preditivo diferente.



Classificador e Regressor. (Não entendi seu significado pelo vídeo.)

Variáveis preditoras → Alg. → classe (são as respostas que precisamos)

**Representação** : Criar um modelo de resultados que o alg. pode aprender. (Universo de teste de hipótese)

**Avaliação**: Determinar modelo que avalia melhor os resultados esperados. 

**Otimização**: Qual dos modelos melhor resolve o modelo em questão?

Ficar atento a falsos positivos. 



Funções de custo,objetivo,erro... verifica o quão bem um Alg. mapeia a função alvo. 



Hipótese g: x → y (Relacionamento de x aproximação de y) Este espaço de hipóteses são o conjunto de hipóteses que podem ser geradas pelo Alg. 

logo: Modelo de aprendizagem = Espaço de Hipóteses + Algoritmos de Aprendizagem. Exemplo: 



![opera_ch6BSux2CW](C:\Users\55319\Documents\ShareX\Screenshots\2019-10\opera_ch6BSux2CW.png)



Se não houver hipótese, não há padrão. Logo pode não haver solução. Pois o espaço de hipótese é o que tem os recursos a serem trabalhados.

Criar modelagens preditivas, mas não algoritmos do zero, pois os mesmos, já existem em bibliotecas do python e R por exemplo.

Alguns algoritmos:  ![opera_urttgPZhXl](C:\Users\55319\Documents\ShareX\Screenshots\2019-10\opera_urttgPZhXl.png)

Para saber mais somente no curso de machine learning...

 