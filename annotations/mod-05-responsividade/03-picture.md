# Picture

Vamos aprender como usar a tag picture para realizar a troca de imagem em nossa web-page de acordo com o tamanho de 
nosso device.

Na tag picture, a priori iremos adicionar um uma tag img. Que será a imagem default. Caso não adicionarmos outra img
ela será a imagem definida para todos os tamanhos.

~~~ html
<picture>
<img src="g.svg">
</picture>
~~~

Agora podemos add uma tag filha de picture chamada **source**, nos iremos utilizar duas propriedades a **media** e *srcset*
a media para definir em um tamanho mínimo para renderizar a img que definiremos o path em srcset. Ao atingir esse min-width. A img
volta a ser a default.

~~~ html
<picture>
    <source media="(min-width:770px)" srcset="image-renderiza-ate-min-width-definido.svg">
    <img src="imagem-default">
</picture>
~~~

Podemos add novas source. Por exemplo podemos definir uma imagem que perdura do 769 até 426

~~~ html
<picture>
    <source media="(min-width:770px)" srcset="image-renderiza-ate-min-width-definido.svg">
    <source media="(min-width:426px)" srcset="image-renderiza-ate-min-width-definido.svg">
    <img src="imagem-default">
</picture>
~~~