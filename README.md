# Análise dos Dados do Titanic
O Conjunto de dados foi o "titanic-data-6.csv". Esse conjunto de dados tem por informação alguns dados dos que foram sobrevivente ou mortos.

Foram respondidas as seguintes perguntas:

1 - Entre as pessoas que sobreviveram e as pessoas mortas, quais tiveram um maior número?<br />
2 - Qual grupo por faixa etária, teve a maior taxa de sobrevivência?
3 - Entre as classes que haviam no Titanic, qual sofreu maior perda?
4 - Por sexo, qual teve maior perda significativa?

Breve Descrição:

Depois de carregar os dados do csv, foi possível observar os dados e assim constatei que os campos (Sobrevivente, Idade, ClasseBilhete, Sexo), seriam ideais para identificar os tipos de pessoas que tenham morrido ou sobrevivido ao infeliz acidente.

Limpezas:

Foi verificado que o campo de ano contia valores nulos e com isso, todo valor nulo foi ajustado a média entre eles. Havia também registros com o tipo float e o mesmo foi convertido para inteiro;

Os campos foram renomeados;

Verificado se existem registros duplicados;

Uma nova coluna para foi criada para categorizar a faíxa etária;

O campo Sexo foi ajustado para male == M e female == F.

Gráficos:

Estes foram feitos todos com gráfico de barras e tentando ao máximo trazer ao analista, maior clareza em relação aos dados utilizados e respondendo de forma simples e objetiva as perguntas que foram sugeridas.
