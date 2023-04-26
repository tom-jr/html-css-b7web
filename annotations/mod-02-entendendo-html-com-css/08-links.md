# Links
Ja foi explicado que o elemento a tem a possibilidade de nos redirecionar para um link interno ou externo 
a nossa application.
Aprofundando sobre a tag. 
o content de uma link pode ser uma imagem tbm. ou ambos
~~~ html
<a href="path">
    <img src="path"/>
</a>
~~~
Um elemento link pode redirecionar para conteúdo da própria pagina adicionando como href o id de outro elemento

Um elemento pode ter suas propriedades modificadas quando esta sob um estado especifico. Por exemplo o link tem mais
estados como o mouseover que no css é reconhecido como **hover**
ex:
~~~ css
a:hover {
    color: red;
}

a:visited {
    color: blue;
}
~~~

~~~ html
<a href="#id_of_element">go to element</a>

<div id="id_of_element"></div>
~~~

## target
O atributo target com o valor **__blank_** define o redirecionamento para uma nova aba do navegador

## title
O atributo title define o um valor ao posicionar o mouse acima do link(mouseover).

