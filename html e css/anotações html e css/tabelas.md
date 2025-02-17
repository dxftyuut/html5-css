
hierarquia de tabela simples

tables > table rous  > table header > table data

nas tabelas você pode usar a teg text-aling e escolher onde o texto vai estar exemplo 

text-aling: rigt, left, bottom, top e midle (não e center e midle)

o padrão do exel e fixar um número no lado direito quando o dado da tabela for apenas números.

oque cada teg faz.

tabelas grandes anatomia.
Thead (cabeça)
	 TR, TD, TH
Tbody
    TR, TD, TH
Tfoot 
    TR, TD, TH

para alinhar dados da tabela horizontalmente use a teg text align left, rigt e midle

para alinhar verticalmente use a teg 
vertical align top, midle e bottom

para fazer uma tabela listrada você usa a tag 

tbody > tr: nth-child(odd) (odd significa impar)

isso tem que ser feito dentro do style, e apos escrever oque esta acima abra {} e escreva backgroundcolor ( a cor que você quer).


![[tabelas.png]]

assim você faz um cabeçalho fixo na tabela.

para fazer um dado da tabela  ocupar mais de uma linha ou coluna. para linha você usa
rowspan="quantidade que ele vai ocupar" e 
colspan="número de colunas"