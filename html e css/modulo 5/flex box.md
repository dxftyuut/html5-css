
existe a flex box pai e a flex box filho, a flex box pai e a maior onde os filhos ficam dentro

display flax = pai

display auto filho

flex-direction

quando você cria do display flex a direção dele e apontada em row autotomaticamente

(flex-direction row = linha horizontal da esquerda para direita)

(flex-direction: row-reverse= linha horizontal da direita para a esquerda)

(flex-direction: colum=linha vertical de cima para baixo ;)
(colum-reverse: linha vertical de cima para baixo)



![[anotação flex box.png]]


os quadros amarelos são oque vão se deslocar ao limite de diminuimento da pagina 

sempre vão diminuir na direção do cross-axis

justify-content altera apenas a linha main-axis

dentro do main-axis temos o mais start que e de onde começa o nosso conteiner, e o main end que e o local final

modos de distribuição no justify-content:

![[justfy].png]]

![[exemplo 1.png]]

exemplo de alinhamento dos itens em flex box

///////////////////////////////////////////////////////////////////////////////////

![[6yfyiuf.png]]

aling-content: stretch significa que os itens dentro do conteiner vão pegar a direção do eixo transversal e vai ocupar o espaço em branco

////////////////////////////////////////////////////////////////////////////////////////////////////////////////

![[4rr.png]]
deixa um espaço em branco no meio

////////////////////////////////////////////////////////////////////////////////////////////////////////////////

![[ytty.png]]

deixa espaços no start, center e end, do mesmo tamanho

////////////////////////////////////////////////////////////////////////////////////////////////////////////////

![[fyf.png]]


1- jUSTIFY-CONTENT : serve para alinhar o conteúdo, alinhar os itens dentro do eixo principal.
2- ALIGN-ITEMS: serve para alinhar os conteúdos, itens dentro do eixo transversal. 
3- ALIGN-CONTENT: serve para alinhar os elementos do eixo transversal quando eles estão empacotados.

o aling content e usado apenas apenas quando o wrap também e usado


flex-basis: auto;
significa que o tamanho do seu conteudo influencia diretamente no tamanho do seu item

flex-basis 
não use width nem height use apenas flex basis
exemplo:
flex-basis: 200px 
esse e o tamanho do seu item 
![[red.png]]


![[tamanhos.png]]

cima: tamanho normal

meio: tamanho grande

baixo: tamanho pequeno

Para quem ficou com dúvida sobre a proporção: Exemplo: Contêiner: 600px Item 1: flex-basis: 150px, flex-grow: 1 Item 2: flex-basis: 150px, flex-grow: 2 Item 3: flex-basis: 150px, flex-grow: 0 O tamanho total dos itens é a soma entre eles (px): 150px + 150px + 150px = 450px. Como o contêiner tem 600px, o espaço vazio é: 600px - 450px = 150px Agora, vamos calcular em quantas partes o espaço vazio será dividido (flex-grow): Item 1: 1 parte Item 2: 2 partes Total: 3 partes (soma entre os itens) O item 1 crescerá em 1/3 dos 150px, ou seja, uma parte de três, adicionando 50px O item 2 crescerá em 2/3 dos 150px, ou seja, duas partes de três, adicionando 100px Tamanho total dos itens: item 1 = 150px + 50px = 200px item 2 = 150px + 100px = 250px Outro exemplo: Contêiner: 600px Item 1: flex-basis: 100px, flex-grow: 3 Item 2: flex-basis: 50px, flex-grow: 1 Item 3: flex-basis: 100px, flex-grow: 2 O tamanho total dos itens é a soma entre eles (px): 600px - 250px , o espaço vazio é 350px Vamos calcular em quantas partes o espaço vazio será dividido (flex-grow): Item 1: 3 partes Item 2: 1 parte Item 3: 2 partes Total: 6 partes (soma entre os itens) O item 1 crescerá em 3/6 dos 350px, ou seja, uma parte de seis, adicionando 175px. O item 2 crescerá em 1/6 dos 350px, ou seja, duas partes de seis, adicionando 58px O item 3 crescerá em 2/6 dos 350px, ou seja, três partes de seis, adicionando 116px Tamanho total dos itens: item 1 = 100px + 175px = 275px item 2 = 50px + 58px = 108px item 2 = 100px + 116px = 216px O cálculo para encontrar as partes é simples: divida o valor total do espaço vazio (350px) pelo total de partes (6). neste caso o resultado foi 58,33px por parte. Em seguida, multiplique as partes atribuídas a cada item por esse valor: item1 = 3 x 58,33 = 175 item 2 = 1 x 58,33 = 58 item 3 = 2 x 58,33 = 116


ao inves de colocar no seu codigo

flex-basis: 150px ;
flex-grow: 0 ;
flex-shrimk:1 ;

coloque 

flex: (grow) (shrink) (basis) ;

exemplo 
flex: 0 1 150px

flex padrão

quando você cria um flex o numero padrão e
flex: 0 1 auto
para simplificar
flex: initial


flex: 0 0 auto
ou 
flex: none

elementos não flexivel

flex: 1 1 auto

o limite de aumentar e diminuir depende do pai




