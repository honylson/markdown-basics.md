#Noções básicas de remarcação

markdown: permite-lhe escrever usandor um facil de ler, facilde escrever formata texto simples que então se converte em HTML válida no gitbug escrita basica 

#escrita básica

###parágrafo

Parágrafos em Markdown são apenas uma ou mais linhas de texto consecutivos, seguido de uma ou mais linhas em branco

Em 2 de julho, uma nave-mãe alienígena entrou em órbita da Terra e implantado várias dezenas em forma de pires nave espacial "destruidor", a cada 15 milhas (24 quilômetros) de largura.

Em 3 de julho, os Cavaleiros Negros, um esquadrão de Marine Corps F / A-18 zangões, participou de um assalto em um destruidor perto da cidade de Los Angeles.

###Cabeçalhos

Você pode criar um título, adicionando um ou mais # símbolos antes de seu texto de título. O número de # você usa irá determinar o tamanho do cabeçalho.

    # O maior título (uma tag <h1>)
     ## A segunda maior rubrica (um <h2> tag)... 
      ###### O 6º maior título (um <h6> tag)

###Bloco de citação

você pode indicar bloco de citação com um >

Nas palavras de Abraham Lincoln:

perdão meu francês

###texto estilo

Você pode fazer o texto em negrito ou itálico.


     * Este texto será itálico *
   
       ** Este texto vai ser ousado **

Ambos negrito e itálico pode usar um * ou um _ em torno do texto para o estilo. Isso permite que você combinar os dois em negrito e itálico, se necessário.

** Todos _deve_ participar da reunião às 5 horas de hoje. **

#Listas

 
### Listas não ordenadas


Você pode fazer uma lista desordenada precedendo itens da lista ou com um * ou um - .
   
    
      * Item
     * Item
     * Item
     - artigo
     - artigo
     - artigo
  
###listas ordenadas

Você pode fazer uma lista ordenada precedendo itens da lista com um número.

1. Item 1
2. Item 2
3. Item 3

###Listas aninhadas

Você pode criar listas aninhadas pelo recuo itens da lista por dois espaços.

    1. Item 1 
    1. Um corolário do item acima. 
    2. No entanto, outro ponto a considerar. 
    2. Número 2 
    * Um corolário que não precisam ser solicitados. 
    * Este é recuado quatro espaços, porque é dois espaços mais longe do que o item acima. 
    * Você pode querer considerar fazer uma nova lista. 
    3. Item 3
  
#A formatação do código

###Formatos em linha

Use Bloco de citação simples ( ` ) para formatar o texto em um formato especial monospace. Tudo dentro dos acentos graves aparecem como está, sem nenhuma outra formatação especial.

    Aqui está uma idéia: por que não vamos tomar `projeto superio` e transformá-lo em` ** ** projeto` razoável.

###Várias linhas

Você pode usar acentos graves triplos ( `` ` ) para formatar o texto como seu próprio bloco distinta.

    Confira este programa limpo eu escrevi:

    `` ` 
    x = 0 
    x = 2 + 2 
    que é x 
     `` `

###as ligações

Você pode criar uma ligação em linha por envolvimento texto da ligação entre colchetes ( [] ), e, em seguida, envolver a ligação entre parênteses ( () ).

Por exemplo, para criar um hiperlink para www.github.com , com um texto de link que diz, Visita GitHub !, você escreveria isso em Markdown: [Visite GitHub!] (www.github.com) .
