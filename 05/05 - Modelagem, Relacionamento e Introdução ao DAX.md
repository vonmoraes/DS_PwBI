**05 - Modelagem, Relacionamento e Introdução ao DAX**

Data Analicts Expressions → DAX (Nome bonito para fórmulas do Excel)

Relacionamento (e Cardinalidade) Modelagem mal feita causa impacto de lentidão, referencial ou não gravar informações. (TOMAR MUICO CUIDADO COM OS RELACIONAMENTOS!)

→ tabelas com cardinalidade \*-\* necessitam de um homem do meio (para serem realizadas)

**M-Language x DAX**

Formulas de colunas personalizadas são em M-language. 

Formulas de colunas personalizadas no data-view são em DAX. 

Exemplo uma nova coluna com DAX & uma nova coluna com M: 

em M Coluna = \[dado]&[dado]

em DAX Coluna = CONCAT(\[dado]&[dado]) ou seja

criamos colunas calculadas, onde há uma expressão que gera o valor da coluna

