# Width Height

Usamos para definir largura e altura de um elemento html
~~~ css
h1 {
    width: 10px;
    height: 10px;
}

h2 {
    width: 10%;
    height: 10%;
}

h3 {
    width: inherit;
    height: inherit;
}
~~~

Os valores podem ser definidos de varias formas. O **_inherit_** define o valor igual ao valor do
elemento que o tem como pai.

Um elemento tem o tamanho final somado com sua borda e padding. Utilizamos o comando box-sizing: border-box;
manteremos o tamanho do elemento idem dos tamanhos de border e padding

~~~ css
* {
    box-sizing: border-box;
}
~~~
utilizamos o '*' para dizer que o comportamento entre chaves será aplicado para todos os el's da page html.