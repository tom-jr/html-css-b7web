# CSS, o que é e como usar

Css basicamente é um formatador. Varias tags básicas do html já tem uma formatação pre-definida. Mas para uma formatação
mais complexa e com bastante opções foi criado o CSS. A tres formas de definir css
- **Inline**: definir css na própria tag html:
Definindo uma cor para o header direto na tag. a cor pode ser definido de mais formas. Porém vamos verificar melhor no futuro.
Adicionando o ';' podemos continuar adicionando mais definições html

~~~ html
<h1 style="color:red; font-size:20px;">header</h1>
~~~

- **Interno**: CSS interno é uma definição de uma tag interna. Onde adicionamos uma tag <style></style> e dentro dela
definimos o css. Esse modo pode ser usado junto ao inline.

ex:
~~~ html
<!DOCTYPE html>
<html>
    <meta charset="UTF-8"/>
    <head>
        <title>Titulo da Pagina</title>
        <style>
            h1 {
                color: red;
                font-size: 20px;
            }
        </style>

    </head>
    
    <body>
        <h1>Header 001</h1>
    </body>
</html>
~~~

- **Externo**: Caso onde o css esta definido em um arquivo externo com extensão .css
e adicionamos a referencia ao objeto por meio da tag link

~~~ html
<link rel="stylesheet" href="path_css_archive.css">
~~~

