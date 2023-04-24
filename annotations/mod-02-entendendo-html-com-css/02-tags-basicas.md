# Tags Básicas

## h1
H1 é uma tg de header que destaca texto definido no html, existe 6 níveis possíveis [h1, h2, ..., h6]
onde h1 é de maior importância e h6 menor importância.
As tags de header são utilizado pelos motores de buscar para optimizar os resultados de pesquisas. Considerando as 
informações entre as tags como match para as buscas realizadas pelos usuários.
~~~ html
<h1>Header 01</h1>
<h2>Header 02</h2>
<h3>Header 03</h3>
<h4>Header 04</h4>
<h5>Header 05</h5>
<h6>Header 06</h6>
~~~

## p
Tag de paragrafo. Realmente básica. Define um paragrafo com o conteúdo envolto da tag

~~~ html
<p>paragraph content</p>
~~~

## a
Tag de ancore(link). Serve para definir um link de redirecionamento em nossa pagina html. Entre a tag 
fica o nome do link, e nas properties definimos dados como o **_href_** que é a property que define o link
de redirecionamento.
~~~ html
<a href="https://www.google.com">Googles</a>
~~~


## img
Tag de imagem, serve para definição e formatação básica de uma imagem na pagina html. Com properties como:
- **_src_**: o source define o path, online ou local onde a imagem esta.
- **_alt_**: define um nome que é renderizado quando a imagem ainda não foi carregada ou não renderizou por algum
erro.


## button
Tag de botão. Define um botão em nosso html, na aula não é apresentado nenhuma property.
~~~ html
<button> Click on me </button>
~~~
## br
Tag de quebra de linha, como explicado no mod anterior, é uma tag de vazia, onde a tag se fecha automaticamente
por não ter a necessidade de um conteúdo.
~~~ html
content 001
<br/>
<br/>
content 002
~~~


## ul ol 
são tags de listas, onde **ul** é para definir listas desordenadas e **ol** para definir listas ordenadas. Ambas as
tags tem uma subTag **li** que define cada conteúdo.

~~~ html
<ul>
    <li> content 001<li>
    <li> content 002<li>
    <li> content 003<li>
</ul>

<ol>
    <li> content 001<li>
    <li> content 002<li>
    <li> content 003<li>
</ol>
~~~

