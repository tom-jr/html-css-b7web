# Cores
Podemos definir cores de 3 formas
- **color-name**: onde definimos o valor da cor pelo seu nome

~~~ css
h1 {
    background-color: red;
}
~~~

- **rgb(n,n,n)**: definimos as cores por valores rgb, onde a range de n é de 0 a 255.
~~~ css
h1 {
    background-color: rgb(255,0,0);
}
~~~

- **Hexadecimal**: definimos a cor por valor hexadecimal. Onde cada par representa o valor de rgb

|red|green|blue|
|--|--|--|
|FF|FF|FF|

~~~ css
h1 {
    background-color: #FF0000;
}
~~~

- **hsl(n%, n%, n%)** define como o rgb, mas em vez de números literais usamos valores de porcentagem
~~~ css
h1 {
    color: hls(100%, 0%, 0%);
}
~~~

- **currentColor**: pega o ultimo valor de color aplicado no próprio elemento ou no pai e usa onde definirmos