# Formatação de Texto no CSS

Alguns css que são usados para formatar o texto:

1. color: rgb|name|hexadecimal.
2. font-size: FontName. Podemos adicionar fonts backup caso a font que selecionamos não esteja disponível no SO do user ele pode usar
a proxima opção, basta declarar mais fontes separando-as com virgular
~~~ css
p {
    font-family: Option_001, Option_003, Option_003; 
}
~~~

3. font-weight: bold. Define o nível de negrito.
4. text-align: left|center|right. alinhamento do texto referente a um content
5. text-decorator: underline. Diz por sim propriedade para decorar o texto, neste caso esta deixando-o com underline
6. text-transformer: uppercase|lowercase. transformação.
7. letter-spacing: (n)px. espaçamento entre letras
8. word-spacing: (n)px. espaçamento entre as palavras
9. line-height: (n)px. espaçamento de linhas
10. text-shadow
primeiro param é de posição x da sombra, segundo param é de posição y da sombra, terceiro param de nível de blur da sombra 
e o quarto é a cor da sombra
~~~ css
p {
    text-shadow: 2px 2px 2px gray;
}
~~~ 

