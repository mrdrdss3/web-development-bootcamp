# HTML

Define o conteúdo e estrutura do website
HTML significa hypertext markup language
hypertext - texto que linka a outros websites, hyperlink, é a base de um website.
markup language - utiliza HTML tags para informar o estilo das letras como negrito, título, etc.
O CONTEÚDO APRESENTA UAM APARÊNCIA DIFERENTE DEVIDO AOS EXEMPLOS E PELA SEMELHANÇA ENTRE O MD E O HTML.
OS EXEMPLOS NÃO SERÃO POSSÍVEIS DE VER NA PREVIEW.

## Heading elements

heading element - <h1>Hello World</h1>
o hello world é o conteúdo, basicamente diz que nós queremos criar um cabeçalho (heading) que contém as palavras "Hello World"
tag - dentro dos <>, o <h1> é a tag de abertura e o </h1> é a tag de fechamento.
elemento - <h1> Hello World </h1>, tanto as tags quanto o conteúdo.
Possuem um nível de hierarquia como por exemplo um sumário.
Exemplo: 
1 - h1 (nível de hierarquia no HTML)
2 - h1 (nível de hierarquia no HTML)
2.1 - h2 (nível de hierarquia no HTML)
2.1.2 - h3 (nível de hierarquia no HTML)
2.2 - h2 (nível de hierarquia no HTML)
3 - h1 (nível de hierarquia no HTML)

NÃO EXISTE UM H7, O MÁXIMO É O H6 

Os heading elements possuem a mesma estrutura, basta mudar o nível (número). Vai diminuindo o tamanho de acordo com o nível.

NORMALMENTE SÓ EXISTE UM H1, NÃO SE PULA NÍVEIS

## Paragraph element

<p> This is a paragraph </p> - separa os textos em parágrafos
Normalmente quando queremos fazer o web design mas não temos o conteúdo usamos o [Lorem ipsum text](https://www.lipsum.com/) para substituir esse lugar do conteúdo.

## Void element

<hr /> - horizontal rule element - proibido colocar qualquer conteúdo dentro, ele serve para separar dois conteúdos distintos, separa eles por uma linha horizontal.

<br /> - break element - Separar o texto em diferentes linhas como um poema.

É sempre melhor usar o paragraph element do que usar o break element para separar em parágrafos.

## The list elements

- unordered list: cria a "bolinha" de listagem
<ul>
    <li>conteúdo</li> - list items
    <li>conteúdo</li> - list items
</ul> 

- ordered list: cria uma lista numerada
<ol>
    <li>conteúdo</li> - list items #1
    <li>conteúdo</li> - list items #2
</ol> 

Se quisermos que a lista comece a partir de um determinado número colocamos: <ol start = numero_desejado>

## Nesting and Identation

- Podemos colocar uma lista dentro de outra, para fazermos isso colocamos <ul> dentro de um item da lista (depois do texto se sem fechar), quando terminarmos a lista "interna" nos fechamos ela </ul> e a o item da lista </li> e continuamos a lista principal, é chamado de NESTED LIST. NÃO ESQUECER A IDENTAÇÃO.

A IDENTAÇÃO É SUPER IMPORTANTE

## Anchor elements

- Cria hiperlinks:
<tag atributo = valor outroatributo = valor> conteúdo</tag>
<a href = "https do site">This is a link</a>

href (atributo) - adiciona o URL que o superlink deve ir

- Podemos arrastar o conteúdo para outros lugares:
draggable = true
<a draggable=true> This is a link to google</a>

## image element

- Adiciona imagens
<img src="url da imagem" />
src - fonte da imagem

[fonte de imagens aleatórias](https://picsum.photos/)

Se quisermos definir o tamanho da imagem podemos colocar o "https://picsum.photos/" e depois da barra o número. (SÓ FUNCIONA PARA ESSE SITE)
Exemplo: https://picsum.photos/200 

Podemos adicionar também um texto alternativo para a imagem, é bom para pessoas com problemas visuais pois ajuda a descrever a imagem de forma auditiva:
<img src="url da imagem" alt ="forest at sunset"/>
