# Função var

Com 
```css
:root {
    --var-color: black;
    --var-font-size: 14px;
    --var-background-color: yellow;
}
```
O var da a capacidade de usar um valor de property css como uma var. Caso a var seja declarado no escopo do **:root** poderemos nos 
referenciar a aquela var em todo documento css. Mas, caso criarmos em escopo de um el, class ou id. Poderemos nos referenciar aquela
var apenas no escopo onde foi declarada.


Quando a var tem um valor extra separado pela virgula, significa que 
```css
:root {
    background-color: white;
}
body {
    background-color: var(--var-background, #fff);
}
```



```css
:root {
    font-size: --var-font-size: 20px;
}

body {
    font-size: var(--var-font-size, yellow);
}

```


Podemos utilizar o @media para modificar o valor de uma var.
```css
:root {
    --font-size: 30px;
}

body {
    font-size: var(--font-size);
}

@media (min-width: 425px) and (max-width: 770px) {
    :root {
        --font-size: 15px;
    }
}
```