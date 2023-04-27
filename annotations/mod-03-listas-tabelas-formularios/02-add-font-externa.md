# Adicionando Font Externa
Nos Vamos usar o google fonts para adicionar uma font
1. do site pegamos o link da font. Ja tem um campo par copiar com a tag de link adicionado. Bastando declarar em nosso html
~~~ html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Caveat&display=swap" rel="stylesheet">
~~~

2. no css basta declarar a font-family entre aspas simples. Assim o sistema entenderá que se trata de uma font externa
~~~ css
h1 {
    font-family: 'Caveat';
}
~~~

