# Margin & Padding 
Margin é o espaçamento definido depois da borda de um elemento
Padding é espaçamento definido antes da borda

ex:
~~~ css
h1 {
    border: 1px solid red;
    padding: 10px 20px 30px 40px;
    margin: 10px;
}
~~~

Lembrando que muitos elementos html ja vem com os dados de margin e padding pre-definida.

Utilizamos o box-sizing para que o tamanho do content não se altere, e sim se adapte aos dados de padding e margin
~~~ c
* {
    box-sizing: border-box;
}
~~~
