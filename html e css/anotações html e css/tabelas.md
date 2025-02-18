
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

para selecionar linhas e fácil basta na teg style digitar tr e personalizar, agora para personalizar colunas você tem que usar a teg nova que veio com o html 5 que se chama colgrup , dentro desta teg você vai abrir a tegs chamadas col, ( ela nao deve ser fechada com /col, escrava dentro dela mesmo. exemplo:< col exemplo>)

a quantidade de col e a quantidade de tabela e a ordem e da esquerda para direita

exemplo:

![[tabelascol 1.png]]

 depois disso dentro do style coloque col.(a classe que você escolheu e personalize)





